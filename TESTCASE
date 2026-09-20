# 20 TEST CASE KIỂM THỬ API – CAB SYSTEM

## 1. Authentication & Account

| TC       | API                              | Method | Chức năng                        | Tiền điều kiện         | Mô tả kiểm thử                                  | Kết quả mong đợi                                                                       |
| -------- | -------------------------------- | ------ | -------------------------------- | ---------------------- | ----------------------------------------------- | -------------------------------------------------------------------------------------- |
| **TC01** | `/auth/login`                    | POST   | Đăng nhập thành công             | Có tài khoản hợp lệ    | Gửi request với `username` và `password` hợp lệ | API trả **200**, trả về `accessToken`, `tokenType`, `expiresIn` và thông tin tài khoản |
| **TC02** | `/auth/login`                    | POST   | Đăng nhập thất bại               | Có tài khoản           | Gửi username hoặc password không chính xác      | API trả **401 – Sai tài khoản hoặc mật khẩu**                                          |
| **TC03** | `/accounts/{accountId}/password` | PUT    | Đổi mật khẩu                     | Đã đăng nhập và có JWT | Gửi `oldPassword` đúng và `newPassword` hợp lệ  | API trả **200**, thông báo đổi mật khẩu thành công                                     |
| **TC04** | `/accounts/{accountId}/password` | PUT    | Đổi mật khẩu với mật khẩu cũ sai | Đã đăng nhập           | Gửi `oldPassword` không chính xác               | API trả **400 – Mật khẩu cũ không chính xác**                                          |

## 2. Customer

| TC       | API                       | Method | Chức năng                    | Tiền điều kiện | Mô tả kiểm thử                       | Kết quả mong đợi                                  |
| -------- | ------------------------- | ------ | ---------------------------- | -------------- | ------------------------------------ | ------------------------------------------------- |
| **TC05** | `/customers`              | GET    | Xem danh sách khách hàng     | Có JWT hợp lệ  | Gửi request với `page=1`, `size=20`  | API trả **200** và danh sách khách hàng           |
| **TC06** | `/customers/{customerId}` | GET    | Xem thông tin khách hàng     | Có JWT hợp lệ  | Gửi request với `customerId` tồn tại | API trả **200** và thông tin khách hàng tương ứng |
| **TC07** | `/customers/{customerId}` | GET    | Tìm khách hàng không tồn tại | Có JWT hợp lệ  | Gửi `customerId` không tồn tại       | API trả **404 – Không tìm thấy khách hàng**       |

## 3. Booking & Driver Assignment

| TC       | API                            | Method | Chức năng                       | Tiền điều kiện                   | Mô tả kiểm thử                                                   | Kết quả mong đợi                                            |
| -------- | ------------------------------ | ------ | ------------------------------- | -------------------------------- | ---------------------------------------------------------------- | ----------------------------------------------------------- |
| **TC08** | `/bookings`                    | POST   | Đặt xe thành công               | Đã đăng nhập                     | Gửi đầy đủ `pickupLocation`, `destination`, `vehicleType` hợp lệ | API trả **201** và tạo booking với trạng thái ban đầu       |
| **TC09** | `/bookings`                    | POST   | Đặt xe thiếu dữ liệu bắt buộc   | Đã đăng nhập                     | Không gửi một trường bắt buộc như `pickupLocation`               | API trả **400 – Dữ liệu không hợp lệ**                      |
| **TC10** | `/bookings/{bookingId}/cancel` | PUT    | Hủy đặt xe                      | Booking tồn tại và có thể hủy    | Gửi yêu cầu hủy booking                                          | API trả **200**, booking được cập nhật thành trạng thái hủy |
| **TC11** | `/bookings/{bookingId}/assign` | POST   | Phân công tài xế                | Booking tồn tại, tài xế khả dụng | Gửi `driverId` hợp lệ                                            | API trả **200 – Phân công tài xế thành công**               |
| **TC12** | `/bookings/{bookingId}/assign` | POST   | Phân công tài xế không khả dụng | Booking tồn tại                  | Gửi `driverId` của tài xế không khả dụng                         | API trả **400 – Tài xế không khả dụng**                     |

## 4. Trip & Tracking

| TC       | API                            | Method | Chức năng                  | Tiền điều kiện           | Mô tả kiểm thử                          | Kết quả mong đợi                              |
| -------- | ------------------------------ | ------ | -------------------------- | ------------------------ | --------------------------------------- | --------------------------------------------- |
| **TC13** | `/bookings/{bookingId}/accept` | POST   | Tài xế nhận chuyến         | Tài xế được phân công    | Tài xế gửi yêu cầu nhận chuyến          | API trả **200 – Nhận chuyến thành công**      |
| **TC14** | `/trips/{tripId}/status`       | PUT    | Cập nhật trạng thái chuyến | Chuyến xe tồn tại        | Gửi trạng thái hợp lệ như `IN_PROGRESS` | API trả **200** và cập nhật trạng thái chuyến |
| **TC15** | `/trips/{tripId}/location`     | PUT    | Cập nhật vị trí tài xế     | Chuyến xe đang hoạt động | Gửi `latitude` và `longitude` hợp lệ    | API trả **200 – Cập nhật vị trí thành công**  |

## 5. Fare & Payment

| TC       | API                              | Method | Chức năng                           | Tiền điều kiện              | Mô tả kiểm thử                                             | Kết quả mong đợi                                                                           |
| -------- | -------------------------------- | ------ | ----------------------------------- | --------------------------- | ---------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| **TC16** | `/trips/{tripId}/fare/calculate` | POST   | Tính cước chuyến xe                 | Trip tồn tại                | Gửi yêu cầu tính cước                                      | API trả **200** và trả về `baseFare`, `distanceFare`, `timeFare`, `surcharge`, `totalFare` |
| **TC17** | `/payments`                      | POST   | Thanh toán chuyến xe                | Trip có cước cần thanh toán | Gửi `tripId` và phương thức `CASH`, `CARD` hoặc `E_WALLET` | API trả **201 – Tạo giao dịch thanh toán thành công**                                      |
| **TC18** | `/payments`                      | POST   | Thanh toán với dữ liệu không hợp lệ | Có JWT                      | Gửi request thiếu `tripId` hoặc `paymentMethod`            | API trả **400 – Thanh toán thất bại**                                                      |

## 6. Rating & Support

| TC       | API                      | Method | Chức năng          | Tiền điều kiện                              | Mô tả kiểm thử                                              | Kết quả mong đợi                      |
| -------- | ------------------------ | ------ | ------------------ | ------------------------------------------- | ----------------------------------------------------------- | ------------------------------------- |
| **TC19** | `/trips/{tripId}/rating` | POST   | Đánh giá chuyến xe | Chuyến xe đã hoàn tất và chưa được đánh giá | Gửi `rating` trong khoảng **1–5**, có thể kèm comment       | API trả **201 – Đánh giá thành công** |
| **TC20** | `/support/tickets`       | POST   | Tạo yêu cầu hỗ trợ | Đã đăng nhập                                | Gửi `subject` và `description` hợp lệ, có thể chọn priority | API trả **201** và tạo yêu cầu hỗ trợ |
