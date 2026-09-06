# CAB System – Nền tảng đặt xe
B1: XÁC ĐỊNH STAKEHOLDER
Bảng dưới đây xác định các bên liên quan chính của dự án **CAB System – Nền tảng đặt xe**, bao gồm vai trò, mối quan tâm, nhu cầu đối với hệ thống và mức độ ảnh hưởng.

| STT | Stakeholder | Vai trò | Mối quan tâm / Mục tiêu | Nhu cầu đối với hệ thống | Mức độ ảnh hưởng |
|:---:|---|---|---|---|:---:|
| **1** | **Ban giám đốc / Chủ doanh nghiệp** | Người quyết định và tài trợ dự án | Muốn hệ thống hoạt động ổn định, mở rộng được và mang lại hiệu quả kinh doanh | Báo cáo số lượng chuyến, doanh thu, tỷ lệ hoàn thành/hủy, hiệu quả tài xế; hệ thống có khả năng mở rộng | **Cao** |
| **2** | **Khách hàng** | Người sử dụng dịch vụ đặt xe | Đặt xe nhanh, biết rõ trạng thái chuyến và thanh toán thuận tiện | Đăng ký/đăng nhập, quản lý thông tin, đặt xe, theo dõi tài xế, xem lịch sử, thanh toán, đánh giá | **Cao** |
| **3** | **Tài xế** | Người nhận và thực hiện chuyến xe | Nhận chuyến phù hợp, cập nhật trạng thái và quản lý hoạt động | Đăng ký/được tạo tài khoản, quản lý hồ sơ, phương tiện, trạng thái hoạt động, nhận/từ chối chuyến, cập nhật trạng thái | **Cao** |
| **4** | **Nhân viên vận hành** | Quản lý và hỗ trợ hoạt động đặt xe | Theo dõi và xử lý các chuyến xe, tài xế và sự cố | Quản lý khách hàng, tài xế, phương tiện, chuyến đi; theo dõi chuyến đang diễn ra; xử lý chuyến lỗi; tra cứu giao dịch | **Cao** |
| **5** | **Quản trị viên hệ thống (System Admin)** | Quản trị hệ thống và phân quyền | Đảm bảo hệ thống an toàn, ổn định và kiểm soát truy cập | Quản lý tài khoản, phân quyền, cấu hình hệ thống, theo dõi nhật ký thao tác, bảo mật dữ liệu | **Cao** |
| **6** | **Nhà cung cấp dịch vụ thanh toán** | Cung cấp cổng thanh toán điện tử | Giao dịch được xử lý chính xác và an toàn | Tiếp nhận yêu cầu thanh toán, trả kết quả giao dịch thành công/thất bại, hỗ trợ xử lý lại | **Trung bình** |
| **7** | **Nhà cung cấp dịch vụ thông báo** | Cung cấp SMS/Email/Push Notification | Đảm bảo thông báo được gửi đến đúng đối tượng | Gửi thông báo đặt xe, tài xế nhận chuyến, tài xế đến, hoàn thành chuyến, kết quả thanh toán | **Trung bình** |
| **8** | **Bộ phận chăm sóc khách hàng / hỗ trợ** | Tiếp nhận và xử lý yêu cầu hỗ trợ | Giải quyết khiếu nại, sự cố và thắc mắc của khách hàng | Tra cứu thông tin chuyến đi, lịch sử giao dịch, hỗ trợ các trường hợp chuyến lỗi/thanh toán lỗi | **Trung bình** |
| **9** | **Bộ phận kế toán / tài chính** | Theo dõi doanh thu và giao dịch | Đảm bảo số liệu doanh thu, thanh toán chính xác | Tra cứu giao dịch, doanh thu, trạng thái thanh toán và đối soát | **Trung bình** |
| **10** | **Đội ngũ phát triển / kỹ thuật** | Xây dựng và bảo trì hệ thống | Hệ thống dễ phát triển, bảo trì và mở rộng | Kiến trúc linh hoạt, các thành phần có thể mở rộng độc lập, triển khai tính năng từng phần | **Trung bình** |
| **11** | **Business Analyst (BA)** | Phân tích và làm rõ yêu cầu | Đảm bảo yêu cầu nghiệp vụ được xác định đầy đủ, chính xác | Xác định phạm vi, stakeholder, quy trình, yêu cầu chức năng/phi chức năng, quy tắc nghiệp vụ và ngoại lệ | **Cao** |
| **12** | **Cơ quan quản lý / pháp lý** | Giám sát việc tuân thủ quy định | Bảo vệ dữ liệu và tuân thủ các quy định liên quan | Hệ thống bảo mật, kiểm soát dữ liệu cá nhân, lưu vết thao tác và đáp ứng yêu cầu pháp lý | **Thấp – Trung bình** |

B2: STAKEHOLDER MATRIX
## Stakeholder Matrix

Stakeholder Matrix được sử dụng để phân loại các bên liên quan dựa trên hai tiêu chí:

- **Power:** Mức độ quyền lực / ảnh hưởng đến dự án.
- **Interest:** Mức độ quan tâm đến hệ thống.

|  | **Interest thấp** | **Interest cao** |
|---|---|---|
| **Power cao** | **KEEP SATISFIED**<br><br>Cơ quan quản lý / pháp lý | **MANAGE CLOSELY**<br><br>Ban giám đốc<br>Khách hàng<br>Tài xế<br>Nhân viên vận hành<br>Quản trị viên hệ thống |
| **Power thấp** | **MONITOR**<br><br>Đội ngũ phát triển / kỹ thuật | **KEEP INFORMED**<br><br>CSKH<br>Kế toán / tài chính<br>Nhà cung cấp thanh toán<br>Nhà cung cấp thông báo |


B3: XÁC ĐỊNH YÊU CẦU KHÁCH HÀNG THÀNH MỤC TIÊU NGHIỆP VỤ BẰNG BG 
## Business Goals – Mục tiêu nghiệp vụ

### 1. Tổng quan

Từ yêu cầu của Công ty ABC, Business Analyst xác định các **Mục tiêu nghiệp vụ (Business Goals – BG)** nhằm làm rõ những kết quả mà doanh nghiệp mong muốn đạt được khi triển khai hệ thống CAB System.

Các mục tiêu này là cơ sở để tiếp tục xác định:

> **Business Goal → Business Requirement → Functional Requirement → Use Case → System Solution**

---

### 2. Danh sách mục tiêu nghiệp vụ

| Mã BG | Mục tiêu nghiệp vụ | Kết quả kỳ vọng |
|:---:|---|---|
| **BG01** | **Xây dựng nền tảng đặt xe trực tuyến tập trung** | Khách hàng có thể thực hiện toàn bộ quy trình đặt xe trên một nền tảng thống nhất. |
| **BG02** | **Nâng cao hiệu quả phân công tài xế** | Tự động tìm và ưu tiên tài xế phù hợp, gần khách hàng, giảm thời gian phân công. |
| **BG03** | **Cải thiện trải nghiệm đặt và theo dõi chuyến đi** | Khách hàng biết trạng thái đặt xe, tài xế nhận chuyến và thời gian dự kiến đến. |
| **BG04** | **Quản lý tập trung thông tin chuyến đi và giao dịch** | Doanh nghiệp có dữ liệu đầy đủ về chuyến đi, thanh toán và lịch sử giao dịch. |
| **BG05** | **Đảm bảo quá trình thực hiện chuyến xe được kiểm soát** | Theo dõi được tiến trình từ khi tài xế nhận chuyến đến khi hoàn thành. |
| **BG06** | **Đảm bảo tính cước và thanh toán thuận tiện, an toàn** | Tính đúng cước, hỗ trợ tiền mặt và thanh toán điện tử, hạn chế rủi ro bảo mật. |
| **BG07** | **Nâng cao hiệu quả thông báo và phối hợp** | Khách hàng, tài xế và nhân viên nhận được thông tin kịp thời. |
| **BG08** | **Nâng cao hiệu quả quản lý và vận hành** | Nhân viên có công cụ tập trung để giám sát và xử lý các vấn đề phát sinh. |
| **BG09** | **Tăng cường bảo mật và kiểm soát hệ thống** | Dữ liệu được bảo vệ, quyền truy cập được kiểm soát và các thao tác quan trọng được lưu vết. |
| **BG10** | **Đảm bảo hệ thống hoạt động ổn định khi nhu cầu tăng cao** | Hệ thống duy trì hoạt động ổn định trong các thời điểm cao điểm. |
| **BG11** | **Nâng cao khả năng mở rộng và phát triển hệ thống** | Có thể bổ sung dịch vụ, phương thức thanh toán và kênh thông báo mới mà không phải xây dựng lại toàn bộ hệ thống. |
| **BG12** | **Hỗ trợ quản lý và ra quyết định dựa trên dữ liệu** | Ban lãnh đạo có báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế. |
| **BG13** | **Nâng cao chất lượng dịch vụ thông qua phản hồi khách hàng** | Doanh nghiệp sử dụng đánh giá của khách hàng để theo dõi và cải thiện chất lượng dịch vụ. |
| **BG14** | **Chuẩn hóa quy trình và chính sách vận hành** | Xác định rõ cách tính cước, ưu tiên tài xế, thời gian phản hồi, hủy chuyến, mất kết nối và lưu trữ dữ liệu. |

---

## 3. Phân nhóm Business Goals

| Nhóm | Business Goals | Trọng tâm |
|---|---|---|
| **Dịch vụ đặt xe** | BG01, BG02, BG03, BG05, BG13 | Cải thiện trải nghiệm khách hàng và hiệu quả chuyến xe |
| **Tài chính và vận hành** | BG04, BG06, BG08, BG12 | Quản lý giao dịch, vận hành và doanh thu |
| **An toàn và ổn định** | BG07, BG09, BG10 | Bảo mật, thông báo và tính ổn định |
| **Phát triển lâu dài** | BG11, BG14 | Khả năng mở rộng và chuẩn hóa nghiệp vụ |

---

## 4. Business Goals trọng tâm

### BG01 – Xây dựng nền tảng đặt xe trực tuyến tập trung

Xây dựng một nền tảng đặt xe trực tuyến giúp khách hàng thực hiện quy trình đặt xe thuận tiện và thống nhất.

### BG02 – Nâng cao hiệu quả phân công tài xế

Tự động xác định tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành.

### BG03 – Cải thiện trải nghiệm theo dõi chuyến đi

Cho phép khách hàng theo dõi quá trình xử lý yêu cầu và trạng thái hiện tại của chuyến xe.

### BG06 – Đảm bảo thanh toán thuận tiện và an toàn

Hỗ trợ nhiều phương thức thanh toán và tích hợp với nhà cung cấp thanh toán bên ngoài mà không lưu trực tiếp thông tin nhạy cảm.

### BG08 – Nâng cao hiệu quả quản lý và vận hành

Cung cấp giao diện quản trị giúp nhân viên theo dõi khách hàng, tài xế, phương tiện và chuyến đi.

### BG09 – Tăng cường bảo mật và kiểm soát hệ thống

Đảm bảo xác thực, phân quyền, bảo vệ dữ liệu cá nhân, dữ liệu vị trí và dữ liệu giao dịch.

### BG10 – Đảm bảo tính ổn định của hệ thống

Đảm bảo hệ thống có thể hoạt động ổn định khi số lượng khách hàng và tài xế tăng cao.

### BG11 – Đảm bảo khả năng mở rộng

Cho phép doanh nghiệp bổ sung các loại dịch vụ, phương thức thanh toán, kênh thông báo và các thành phần kỹ thuật mới trong tương lai.

---

B4: XÁC ĐỊNH MODULE
## Modules – Các module của hệ thống

CAB System được chia thành các module nghiệp vụ chính nhằm đảm bảo hệ thống có cấu trúc rõ ràng, dễ quản lý, phát triển và mở rộng.

| STT | Module | Mô tả | Chức năng chính |
|:---:|---|---|---|
| **1** | **Quản lý tài khoản** | Quản lý tài khoản và thông tin người dùng | Đăng ký, đăng nhập, quản lý thông tin cá nhân, xác thực tài khoản |
| **2** | **Quản lý khách hàng** | Quản lý thông tin và hoạt động của khách hàng | Quản lý hồ sơ, lịch sử đặt xe, lịch sử chuyến đi |
| **3** | **Quản lý tài xế & phương tiện** | Quản lý tài xế, phương tiện và trạng thái hoạt động | Quản lý hồ sơ tài xế, thông tin xe, trạng thái hoạt động, nhận/từ chối chuyến |
| **4** | **Đặt xe & phân công tài xế** | Tiếp nhận yêu cầu đặt xe và tìm tài xế phù hợp | Nhập điểm đón/điểm đến, chọn loại xe, tạo yêu cầu, tìm kiếm và phân công tài xế |
| **5** | **Quản lý chuyến đi** | Quản lý toàn bộ vòng đời của chuyến xe | Theo dõi chuyến đi, cập nhật trạng thái, hoàn thành chuyến, hủy chuyến |
| **6** | **Tính cước & thanh toán** | Tính giá chuyến và xử lý thanh toán | Tính cước, thanh toán tiền mặt, thanh toán điện tử, xử lý giao dịch thất bại |
| **7** | **Thông báo & đánh giá** | Giao tiếp với khách hàng và tài xế trong quá trình sử dụng dịch vụ | Gửi thông báo, cập nhật trạng thái, thông báo thanh toán, đánh giá tài xế |
| **8** | **Quản trị & vận hành** | Hỗ trợ nhân viên vận hành và quản trị hệ thống | Quản lý khách hàng, tài xế, chuyến đi, giao dịch, báo cáo, phân quyền và nhật ký hệ thống |

### Chi tiết các module

#### 1. Quản lý tài khoản

Module quản lý tài khoản chịu trách nhiệm xác thực và quản lý thông tin người dùng trong hệ thống.

**Chức năng:**
- Đăng ký tài khoản.
- Đăng nhập và đăng xuất.
- Quản lý thông tin cá nhân.
- Xác thực tài khoản.
- Quản lý quyền truy cập theo vai trò.

**Actor liên quan:**
- Khách hàng.
- Tài xế.
- Nhân viên vận hành.
- Quản trị viên hệ thống.

#### 2. Quản lý khách hàng

Module quản lý thông tin và hoạt động của khách hàng.

**Chức năng:**
- Quản lý hồ sơ khách hàng.
- Cập nhật thông tin cá nhân.
- Xem lịch sử đặt xe.
- Xem lịch sử chuyến đi.
- Xem thông tin thanh toán và giao dịch.
- Quản lý đánh giá và phản hồi.

**Actor liên quan:**
- Khách hàng.
- Nhân viên vận hành.
- Bộ phận chăm sóc khách hàng.

#### 3. Quản lý tài xế & phương tiện

Module quản lý thông tin tài xế, phương tiện và trạng thái hoạt động.

**Chức năng:**
- Đăng ký hoặc tạo tài khoản tài xế.
- Quản lý hồ sơ tài xế.
- Quản lý thông tin phương tiện.
- Cập nhật trạng thái hoạt động.
- Xác định vị trí tài xế.
- Nhận hoặc từ chối chuyến.
- Theo dõi hiệu quả hoạt động của tài xế.

**Actor liên quan:**
- Tài xế.
- Nhân viên vận hành.
- Quản trị viên hệ thống.

#### 4. Đặt xe & phân công tài xế

Đây là module trung tâm của CAB System, xử lý yêu cầu đặt xe và phân công tài xế.

**Chức năng:**
- Nhập điểm đón.
- Nhập điểm đến.
- Lựa chọn loại xe.
- Tạo yêu cầu đặt xe.
- Tìm kiếm tài xế phù hợp.
- Ưu tiên tài xế phù hợp và ở gần.
- Gửi yêu cầu đến tài xế.
- Xử lý trường hợp tài xế từ chối hoặc không phản hồi.
- Tiếp tục tìm tài xế khác.
- Thông báo cho khách hàng khi không tìm được tài xế.

**Actor liên quan:**
- Khách hàng.
- Tài xế.
- Nhân viên vận hành.


#### 5. Quản lý chuyến đi

Module quản lý toàn bộ vòng đời của một chuyến xe từ khi tạo yêu cầu đến khi hoàn thành.

**Các trạng thái chính:**

```text
Đặt xe
   ↓
Tìm tài xế
   ↓
Tài xế được phân công
   ↓
Tài xế đang đến điểm đón
   ↓
Đã đón khách
   ↓
Đang di chuyển
   ↓
Hoàn thành chuyến
```
B5: THIẾT KẾ BUSINESS REQUIREMENTS KÍ HIỆU BG
## Business Requirements – BG

Business Requirement của CAB System được xác định bằng mã **BG (Business Goal/Business Requirement)**. Các BG mô tả những mục tiêu và yêu cầu ở cấp độ nghiệp vụ mà hệ thống cần đáp ứng nhằm giải quyết các vấn đề của hoạt động đặt xe hiện tại.

| Mã BG | Business Requirement | Mô tả | Stakeholder liên quan | Mức độ ưu tiên |
|:---:|---|---|---|:---:|
| **BG01** | Xây dựng nền tảng đặt xe trực tuyến tập trung | Cho phép khách hàng thực hiện toàn bộ quy trình đặt xe trên một nền tảng thống nhất thay cho phương thức đặt xe thủ công | Ban giám đốc, Khách hàng, Tài xế | **Cao** |
| **BG02** | Nâng cao hiệu quả phân công tài xế | Hỗ trợ xác định và phân công tài xế phù hợp dựa trên vị trí, trạng thái hoạt động và các tiêu chí vận hành | Khách hàng, Tài xế, Nhân viên vận hành | **Cao** |
| **BG03** | Cải thiện khả năng theo dõi chuyến đi | Cho phép khách hàng và nhân viên vận hành theo dõi trạng thái chuyến đi và tình trạng tài xế trong quá trình thực hiện chuyến | Khách hàng, Tài xế, Nhân viên vận hành | **Cao** |
| **BG04** | Quản lý tập trung thông tin chuyến đi | Tập trung dữ liệu đặt xe, chuyến đi, tài xế, khách hàng và trạng thái chuyến để thuận tiện cho việc tra cứu và quản lý | Nhân viên vận hành, CSKH, Ban giám đốc | **Cao** |
| **BG05** | Đảm bảo tính cước và thanh toán thuận tiện | Hỗ trợ xác định chi phí chuyến đi và cung cấp các phương thức thanh toán phù hợp, bao gồm tiền mặt và thanh toán điện tử | Khách hàng, Kế toán/Tài chính | **Cao** |
| **BG06** | Nâng cao hiệu quả quản lý và vận hành | Hỗ trợ nhân viên vận hành theo dõi chuyến đi, tài xế, phương tiện và xử lý các trường hợp phát sinh | Nhân viên vận hành, CSKH | **Cao** |
| **BG07** | Đảm bảo thông tin được thông báo kịp thời | Cung cấp thông báo cho khách hàng và tài xế khi có thay đổi liên quan đến đặt xe, phân công, trạng thái chuyến và thanh toán | Khách hàng, Tài xế | **Cao** |
| **BG08** | Đảm bảo an toàn và bảo mật dữ liệu | Bảo vệ thông tin cá nhân, thông tin tài xế, vị trí, giao dịch và kiểm soát quyền truy cập hệ thống | Quản trị viên, Ban giám đốc | **Cao** |
| **BG09** | Đảm bảo hệ thống hoạt động ổn định | Đảm bảo hệ thống có khả năng hoạt động ổn định khi số lượng yêu cầu đặt xe tăng cao và khi một số dịch vụ bên ngoài gặp sự cố | Ban giám đốc, Đội ngũ kỹ thuật | **Cao** |
| **BG10** | Hỗ trợ mở rộng hệ thống | Thiết kế hệ thống có khả năng mở rộng thêm dịch vụ, phương thức thanh toán, kênh thông báo và các thành phần kỹ thuật trong tương lai | Ban giám đốc, Đội ngũ kỹ thuật | **Trung bình** |
| **BG11** | Hỗ trợ quản lý và ra quyết định dựa trên dữ liệu | Cung cấp báo cáo và thống kê về chuyến đi, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế | Ban giám đốc, Kế toán/Tài chính, Nhân viên vận hành | **Cao** |
| **BG12** | Nâng cao chất lượng dịch vụ | Ghi nhận đánh giá và phản hồi của khách hàng nhằm hỗ trợ doanh nghiệp theo dõi và cải thiện chất lượng dịch vụ | Khách hàng, Ban giám đốc, Nhân viên vận hành | **Trung bình** |

### Phân loại Business Requirements

Các Business Requirements của CAB System được phân thành các nhóm sau:

| Nhóm | Business Requirements | Mục tiêu |
|---|---|---|
| **Quản lý đặt xe** | BG01, BG02, BG03 | Chuẩn hóa và nâng cao hiệu quả quy trình đặt xe và thực hiện chuyến đi |
| **Quản lý vận hành** | BG04, BG06, BG11 | Tập trung dữ liệu, hỗ trợ vận hành và ra quyết định |
| **Thanh toán và dịch vụ** | BG05, BG07, BG12 | Đảm bảo thanh toán thuận tiện, thông tin kịp thời và nâng cao chất lượng dịch vụ |
| **Bảo mật và ổn định** | BG08, BG09 | Đảm bảo an toàn dữ liệu và khả năng hoạt động ổn định |
| **Mở rộng hệ thống** | BG10 | Đảm bảo hệ thống có khả năng phát triển trong tương lai |

## Mối quan hệ Business Requirement

Business Requirement là cơ sở để xác định các yêu cầu chi tiết của hệ thống.

**BG → BR → FR → Use Case → Module**

Trong đó:

- **BG (Business Requirement):** Doanh nghiệp cần đạt được mục tiêu gì?
- **BR (Business Rule):** Nghiệp vụ phải tuân theo quy tắc nào?
- **FR (Functional Requirement):** Hệ thống phải cung cấp chức năng gì?
- **Use Case:** Actor tương tác với hệ thống như thế nào?
- **Module:** Chức năng thuộc phân hệ nào của hệ thống?

B6: MÔ HÌNH HÓA NGHIỆP VỤ BẰNG BUSINESS REQUIREMENTS

Hệ thống CAB được xây dựng xoay quanh 05 quy trình nghiệp vụ trọng tâm, bao quát luồng xử lý từ khi khách hàng đặt xe đến khi chuyến xe hoàn tất và dữ liệu được cập nhật.


### Mục tiêu

Tiếp nhận yêu cầu đặt xe của khách hàng, tìm kiếm tài xế phù hợp và thực hiện phân công tài xế cho chuyến xe.

### Chi tiết quy trình

| STT | Hoạt động | Actor thực hiện | BG liên quan |
|---|---|---|---|
| 1.1 | Khách hàng nhập điểm đón, điểm đến và loại xe | Khách hàng | BG01 |
| 1.2 | Khách hàng gửi yêu cầu đặt xe | Khách hàng | BG01 |
| 1.3 | Hệ thống kiểm tra thông tin yêu cầu | Hệ thống | BG01 |
| 1.4 | Hệ thống tìm kiếm tài xế phù hợp | Hệ thống | BG02 |
| 1.5 | Hệ thống gửi yêu cầu nhận chuyến | Hệ thống | BG02 |
| 1.6 | Tài xế nhận hoặc từ chối chuyến | Tài xế | BG02 |
| 1.7 | Hệ thống xử lý trường hợp tài xế từ chối hoặc không phản hồi | Hệ thống | BG02 |
| 1.8 | Hệ thống xác nhận tài xế được phân công | Hệ thống | BG02 |
| 1.9 | Hệ thống thông báo kết quả phân công cho khách hàng | Hệ thống | BG07 |

### Luồng xử lý

```text
Khách hàng đặt xe
        |
        v
Kiểm tra yêu cầu
        |
        v
Tìm tài xế phù hợp
        |
        v
Gửi yêu cầu nhận chuyến
        |
        v
Tài xế phản hồi
        |
        +------ Từ chối/Không phản hồi
        |                |
        |                v
        |       Tìm tài xế khác
        |                |
        +----------------+
        |
        v
Phân công tài xế
        |
        v
Thông báo khách hàng
```
B7: THIẾT KẾ FUCTIONAL REQUIREMENT - YÊU CẦU CHỨC NĂNG 


## 1. Tổng quan

Functional Requirements (FR) mô tả các chức năng mà hệ thống CAB cần cung cấp để đáp ứng các mục tiêu nghiệp vụ (Business Goals - BG).

Hệ thống được xây dựng xoay quanh 05 quy trình nghiệp vụ trọng tâm:

1. Đặt xe và phân công tài xế
2. Thực hiện và theo dõi chuyến xe
3. Tính cước và thanh toán
4. Đánh giá chuyến xe
5. Hoàn tất và cập nhật dữ liệu

Mỗi Functional Requirement được liên kết với Business Goal tương ứng nhằm đảm bảo khả năng truy xuất từ mục tiêu nghiệp vụ đến chức năng hệ thống.

---

# 2. Functional Requirements

## 2.1. Quy trình 1 - Đặt xe và phân công tài xế

**Mục tiêu:** Tiếp nhận yêu cầu đặt xe, tìm kiếm tài xế phù hợp và thực hiện phân công tài xế.

# B3. FUNCTIONAL REQUIREMENTS (FR)

## 1. Đặt xe và phân công tài xế

| Mã FR | Chức năng | BG |
|---|---|---|
| FR01 | Đặt xe | BG01 |
| FR02 | Kiểm tra thông tin đặt xe | BG01 |
| FR03 | Tìm kiếm tài xế phù hợp | BG02 |
| FR04 | Gửi yêu cầu nhận chuyến | BG02 |
| FR05 | Chấp nhận / từ chối chuyến | BG02 |
| FR06 | Xử lý tài xế từ chối / không phản hồi | BG02 |
| FR07 | Phân công tài xế | BG02 |
| FR08 | Thông báo kết quả phân công | BG07 |

---

## 2. Thực hiện và theo dõi chuyến xe

| Mã FR | Chức năng | BG |
|---|---|---|
| FR09 | Xem thông tin chuyến xe | BG03 |
| FR10 | Cập nhật trạng thái đã đến điểm đón | BG03 |
| FR11 | Cập nhật trạng thái bắt đầu chuyến | BG03 |
| FR12 | Cập nhật trạng thái đang thực hiện chuyến | BG03 |
| FR13 | Theo dõi trạng thái chuyến xe | BG03 |
| FR14 | Cập nhật trạng thái hoàn thành chuyến | BG03 |
| FR15 | Lưu trạng thái chuyến xe | BG04 |

---

## 3. Tính cước và thanh toán

| Mã FR | Chức năng | BG |
|---|---|---|
| FR16 | Xác định thông tin chuyến xe | BG05 |
| FR17 | Tính cước chuyến xe | BG05 |
| FR18 | Hiển thị cước phí | BG05 |
| FR19 | Chọn phương thức thanh toán | BG05 |
| FR20 | Thực hiện thanh toán | BG05 |
| FR21 | Kiểm tra kết quả thanh toán | BG05 |
| FR22 | Xử lý thanh toán thất bại / thanh toán lại | BG05 |
| FR23 | Ghi nhận giao dịch thanh toán | BG04 |

---

## 4. Đánh giá chuyến xe

| Mã FR | Chức năng | BG |
|---|---|---|
| FR24 | Hiển thị chức năng đánh giá | BG12 |
| FR25 | Đánh giá tài xế / chuyến xe | BG12 |
| FR26 | Gửi nhận xét | BG12 |
| FR27 | Lưu đánh giá | BG12 |
| FR28 | Cập nhật dữ liệu đánh giá | BG12 |

---

## 5. Hoàn tất và cập nhật dữ liệu

| Mã FR | Chức năng | BG |
|---|---|---|
| FR29 | Kiểm tra trạng thái chuyến xe | BG04 |
| FR30 | Kiểm tra trạng thái thanh toán | BG05 |
| FR31 | Lưu lịch sử chuyến xe | BG04 |
| FR32 | Lưu thông tin giao dịch | BG04 |
| FR33 | Cập nhật trạng thái tài xế | BG06 |
| FR34 | Cập nhật dữ liệu thống kê, báo cáo | BG11 |
| FR35 | Hoàn tất chuyến xe | BG06 |

---

## Tổng hợp

| Quy trình | Số chức năng |
|---|---:|
| Đặt xe và phân công tài xế | 8 |
| Thực hiện và theo dõi chuyến xe | 7 |
| Tính cước và thanh toán | 8 |
| Đánh giá chuyến xe | 5 |
| Hoàn tất và cập nhật dữ liệu | 7 |
| **Tổng cộng** | **35** |

B8: BUSINESS RULE - QUY ĐINH NGHIỆP VỤ

Quy định nghiệp vụ xác định các nguyên tắc và điều kiện mà hệ thống CAB phải tuân thủ trong quá trình xử lý đặt xe, thực hiện chuyến, thanh toán và hoàn tất chuyến xe.

---

## 1. Quy định đặt xe và phân công tài xế

| Mã BR | Quy định nghiệp vụ |
|---|---|
| BR01 | Khách hàng phải cung cấp đầy đủ thông tin điểm đón, điểm đến và loại xe khi đặt xe. |
| BR02 | Hệ thống chỉ tiếp nhận yêu cầu đặt xe khi thông tin đặt xe hợp lệ. |
| BR03 | Tài xế được phân công phải phù hợp với yêu cầu chuyến xe và đang ở trạng thái có thể nhận chuyến. |
| BR04 | Tài xế có quyền chấp nhận hoặc từ chối yêu cầu chuyến xe. |
| BR05 | Khi tài xế từ chối hoặc không phản hồi, hệ thống tiếp tục tìm tài xế phù hợp khác. |
| BR06 | Một chuyến xe chỉ được phân công cho một tài xế tại một thời điểm. |
| BR07 | Khi tìm được tài xế, hệ thống phải thông báo kết quả phân công cho khách hàng. |
| BR08 | Nếu không tìm được tài xế phù hợp, hệ thống phải thông báo cho khách hàng. |

---

## 2. Quy định thực hiện và theo dõi chuyến xe

| Mã BR | Quy định nghiệp vụ |
|---|---|
| BR09 | Tài xế chỉ được thực hiện chuyến xe khi đã được hệ thống phân công. |
| BR10 | Trạng thái chuyến xe phải được cập nhật theo đúng trình tự nghiệp vụ. |
| BR11 | Tài xế phải cập nhật trạng thái khi đến điểm đón. |
| BR12 | Chuyến xe chỉ được chuyển sang trạng thái đang thực hiện sau khi tài xế đón khách. |
| BR13 | Chuyến xe chỉ được chuyển sang trạng thái hoàn thành khi tài xế kết thúc chuyến. |
| BR14 | Khách hàng chỉ được theo dõi các chuyến xe thuộc tài khoản của mình. |
| BR15 | Hệ thống phải lưu lịch sử thay đổi trạng thái của chuyến xe. |

---

## 3. Quy định tính cước và thanh toán

| Mã BR | Quy định nghiệp vụ |
|---|---|
| BR16 | Cước phí được tính dựa trên thông tin của chuyến xe theo chính sách tính cước của hệ thống. |
| BR17 | Hệ thống phải hiển thị số tiền cần thanh toán trước khi thực hiện thanh toán. |
| BR18 | Khách hàng phải lựa chọn một phương thức thanh toán hợp lệ. |
| BR19 | Hệ thống phải ghi nhận kết quả của mỗi giao dịch thanh toán. |
| BR20 | Giao dịch thanh toán thành công phải được cập nhật trạng thái thành công. |
| BR21 | Khi thanh toán thất bại, hệ thống phải thông báo cho khách hàng. |
| BR22 | Khách hàng có thể thực hiện thanh toán lại theo chính sách của hệ thống. |
| BR23 | Thông tin nhạy cảm của phương thức thanh toán không được lưu trực tiếp trên hệ thống CAB. |
| BR24 | Thông tin giao dịch phải được lưu để phục vụ tra cứu và quản lý. |

---

## 4. Quy định đánh giá chuyến xe

| Mã BR | Quy định nghiệp vụ |
|---|---|
| BR25 | Khách hàng chỉ được đánh giá sau khi chuyến xe hoàn thành. |
| BR26 | Mỗi chuyến xe chỉ được đánh giá theo chính sách đánh giá của hệ thống. |
| BR27 | Đánh giá phải thuộc về đúng chuyến xe và khách hàng thực hiện chuyến. |
| BR28 | Hệ thống phải lưu thông tin đánh giá sau khi khách hàng gửi đánh giá. |
| BR29 | Dữ liệu đánh giá được sử dụng để theo dõi chất lượng phục vụ của tài xế. |

---

## 5. Quy định hoàn tất và cập nhật dữ liệu

| Mã BR | Quy định nghiệp vụ |
|---|---|
| BR30 | Chuyến xe chỉ được hoàn tất khi trạng thái chuyến xe đã được cập nhật hoàn thành. |
| BR31 | Hệ thống phải kiểm tra trạng thái thanh toán trước khi hoàn tất dữ liệu chuyến xe. |
| BR32 | Thông tin chuyến xe phải được lưu vào lịch sử sau khi hoàn tất. |
| BR33 | Thông tin giao dịch phải được lưu và liên kết với chuyến xe tương ứng. |
| BR34 | Sau khi chuyến xe kết thúc, trạng thái tài xế phải được cập nhật để có thể nhận chuyến mới. |
| BR35 | Dữ liệu chuyến xe và giao dịch phải được cập nhật vào dữ liệu thống kê, báo cáo. |

---

# Tổng hợp quy định nghiệp vụ

| Quy trình | Phạm vi BR | Số lượng |
|---|---|---:|
| Đặt xe và phân công tài xế | BR01 - BR08 | 8 |
| Thực hiện và theo dõi chuyến xe | BR09 - BR15 | 7 |
| Tính cước và thanh toán | BR16 - BR24 | 9 |
| Đánh giá chuyến xe | BR25 - BR29 | 5 |
| Hoàn tất và cập nhật dữ liệu | BR30 - BR35 | 6 |
| **Tổng cộng** | **BR01 - BR35** | **35** |

---

# Liên kết giữa BG - FR - BR

```text
Business Goal (BG)
        |
        v
Functional Requirement (FR)
        |
        v
Business Rule (BR)
        |
        v
Use Case (UC)
        |
        v
System Function
```
B9: NGHIỆP VỤ PHI CHỨC NĂNG - NON-FUNCTIONAL REQUIREMENTS (NFR)

Các yêu cầu phi chức năng xác định các tiêu chí về chất lượng, hiệu năng, bảo mật, ổn định và khả năng mở rộng của hệ thống CAB.

| Mã NFR | Nhóm | Yêu cầu phi chức năng | BG |
|---|---|---|---|
| NFR01 | Hiệu năng | Hệ thống phải phản hồi nhanh đối với các thao tác đặt xe và theo dõi chuyến. | BG09 |
| NFR02 | Khả năng chịu tải | Hệ thống phải hoạt động ổn định khi số lượng người dùng và yêu cầu đặt xe tăng cao. | BG09 |
| NFR03 | Tính sẵn sàng | Lỗi của một thành phần như thanh toán hoặc thông báo không được làm dừng toàn bộ quá trình đặt xe. | BG09 |
| NFR04 | Bảo mật | Hệ thống phải xác thực người dùng trước khi truy cập các chức năng yêu cầu đăng nhập. | BG08 |
| NFR05 | Phân quyền | Hệ thống phải kiểm soát quyền truy cập theo vai trò của người dùng. | BG08 |
| NFR06 | Bảo vệ dữ liệu | Thông tin cá nhân, thông tin phương tiện, vị trí và giao dịch phải được bảo vệ. | BG08 |
| NFR07 | Ghi nhật ký | Hệ thống phải ghi nhận các thao tác quan trọng để phục vụ kiểm tra và truy vết. | BG08 |
| NFR08 | Khả năng mở rộng | Hệ thống phải cho phép mở rộng thêm dịch vụ, phương thức thanh toán và kênh thông báo. | BG10 |
| NFR09 | Khả năng bảo trì | Các thành phần của hệ thống nên được thiết kế độc lập để thuận tiện bảo trì và nâng cấp. | BG10 |
| NFR10 | Triển khai | Hệ thống phải hỗ trợ triển khai từng phần với ảnh hưởng tối thiểu đến hoạt động hiện tại. | BG10 |
| NFR11 | Khả năng phục hồi | Hệ thống phải có khả năng xử lý lỗi của các thành phần bên ngoài mà không làm mất dữ liệu chuyến xe. | BG09 |
| NFR12 | Audit | Các thao tác quản trị và thao tác quan trọng phải được lưu vết. | BG08 |
B10: THIẾT KẾ MÔ HÌNH THỰC THỂ KẾT HỢP 

                         +----------------+
                         |    ACCOUNT     |
                         +-------+--------+
                                 |
                    +------------+------------+
                    |                         |
                    v                         v
             +-------------+           +-------------+
             |  CUSTOMER   |           |    DRIVER   |
             +------+------+           +------+------+
                    |                          |
                    |                          v
                    |                   +-------------+
                    |                   |   VEHICLE   |
                    |                   +------+------+
                    |                          |
                    v                          |
             +-------------+                   |
             |   BOOKING   |-------------------+
             +------+------+                   |
                    |                          |
                    +------------+-------------+
                                 |
                                 v
                          +-------------+
                          |     TRIP    |
                          +------+------+ 
                                 |
                    +------------+------------+
                    |                         |
                    v                         v
             +-------------+           +-------------+
             |   PAYMENT   |           |   RATING    |
             +-------------+           +-------------+
      


B11: ERD
+------------------+
|     ACCOUNT      |
+------------------+
| PK AccountID     |
| Username         |
| Password         |
| Role             |
| Status           |
+--------+---------+
         |
         | 1
         |
    +----+----+
    |         |
    |         |
    N         N
    |         |
+---v----+ +--v-------+
|CUSTOMER| |  DRIVER  |
+--------+ +----------+
|PK CustomerID| |PK DriverID|
|FK AccountID | |FK AccountID|
|FullName     | |FullName    |
|Phone        | |Phone       |
|Email        | |LicenseNo   |
|Address      | |Status      |
+-----+-------+ |Location    |
      |         +-----+------+
      |               |
      | 1             | 1
      |               |
      | N             | N
+-----v-------+  +----v-------+
|   BOOKING   |  |  VEHICLE   |
+-------------+  +------------+
|PK BookingID |  |PK VehicleID|
|FK CustomerID|  |FK DriverID |
|Pickup       |  |LicensePlate|
|Destination  |  |VehicleType |
|VehicleType  |  |Brand       |
|BookingTime  |  |Status      |
|Status       |  +-----+------+
+------+------+        |
       |               |
       | 1             | 1
       |               |
       | 0..1          | N
       |               |
       +-------+-------+
               |
               v
        +-------------+
        |     TRIP    |
        +-------------+
        |PK TripID    |
        |FK BookingID |
        |FK DriverID  |
        |FK VehicleID |
        |StartTime    |
        |EndTime      |
        |Fare         |
        |Status       |
        +------+------+ 
               |
          +----+----+
          |         |
          |         |
          v         v
+----------------+ +----------------+
|    PAYMENT     | |     RATING     |
+----------------+ +----------------+
|PK PaymentID    | |PK RatingID     |
|FK TripID       | |FK TripID       |
|PaymentMethod   | |FK CustomerID   |
|Amount          | |FK DriverID     |
|PaymentTime     | |Score           |
|Status          | |Comment         |
|TransactionCode | |RatingTime      |
+----------------+ +----------------+


B12: USE CASE
DANH SÁCH USE CASE

| Mã UC | Tên Use Case | Actor chính |
|---|---|---|
| **UC01** | Đăng nhập | Khách hàng, Tài xế, Nhân viên vận hành, Admin |
| **UC02** | Quản lý thông tin cá nhân | Khách hàng, Tài xế |
| **UC03** | Đặt xe | Khách hàng |
| **UC04** | Tìm kiếm tài xế phù hợp | Hệ thống |
| **UC05** | Phân công tài xế | Hệ thống |
| **UC06** | Nhận / từ chối chuyến | Tài xế |
| **UC07** | Thực hiện chuyến xe | Tài xế |
| **UC08** | Theo dõi chuyến xe | Khách hàng |
| **UC09** | Tính cước chuyến xe | Hệ thống |
| **UC10** | Thanh toán chuyến xe | Khách hàng, Payment Gateway |
| **UC11** | Xử lý thanh toán thất bại | Hệ thống, Payment Gateway |
| **UC12** | Đánh giá chuyến xe | Khách hàng |
| **UC13** | Hoàn tất chuyến xe | Tài xế, Hệ thống |
| **UC14** | Quản lý khách hàng | Nhân viên vận hành, Admin |
| **UC15** | Quản lý tài xế | Nhân viên vận hành, Admin |
| **UC16** | Quản lý phương tiện | Nhân viên vận hành, Admin |
| **UC17** | Theo dõi hoạt động vận hành | Nhân viên vận hành |
| **UC18** | Quản lý tài khoản và phân quyền | Admin |
| **UC19** | Xem báo cáo thống kê | Nhân viên vận hành, Admin |
### Nhóm 1. Quản lý tài khoản
- UC01 – Đăng nhập
- UC02 – Quản lý thông tin cá nhân
- UC18 – Quản lý tài khoản và phân quyền

### Nhóm 2. Đặt xe và phân công tài xế
- UC03 – Đặt xe
- UC04 – Tìm kiếm tài xế phù hợp
- UC05 – Phân công tài xế
- UC06 – Nhận / từ chối chuyến

### Nhóm 3. Thực hiện và theo dõi chuyến xe
- UC07 – Thực hiện chuyến xe
- UC08 – Theo dõi chuyến xe
- UC13 – Hoàn tất chuyến xe

### Nhóm 4. Tính cước và thanh toán
- UC09 – Tính cước chuyến xe
- UC10 – Thanh toán chuyến xe
- UC11 – Xử lý thanh toán thất bại

### Nhóm 5. Đánh giá
- UC12 – Đánh giá chuyến xe

### Nhóm 6. Quản lý và vận hành
- UC14 – Quản lý khách hàng
- UC15 – Quản lý tài xế
- UC16 – Quản lý phương tiện
- UC17 – Theo dõi hoạt động vận hành
- UC19 – Xem báo cáo thống kê
B13: AC - TIÊU CHÍ XÁC NHẬN

| Mã AC | Use Case | Tiêu chí xác nhận |
|---|---|---|
| **AC01** | UC01 - Đăng nhập | Người dùng nhập đúng thông tin đăng nhập thì đăng nhập thành công. |
| **AC02** | UC01 - Đăng nhập | Nhập sai thông tin thì hệ thống thông báo lỗi và không cho truy cập. |
| **AC03** | UC03 - Đặt xe | Nhập đầy đủ điểm đón, điểm đến và loại xe thì có thể gửi yêu cầu đặt xe. |
| **AC04** | UC03 - Đặt xe | Hệ thống kiểm tra thông tin đặt xe trước khi tạo yêu cầu. |
| **AC05** | UC04 - Tìm kiếm tài xế | Hệ thống xác định được tài xế phù hợp. |
| **AC06** | UC05 - Phân công tài xế | Tài xế chấp nhận thì hệ thống ghi nhận tài xế được phân công. |
| **AC07** | UC06 - Nhận / từ chối chuyến | Tài xế có thể chấp nhận hoặc từ chối chuyến. |
| **AC08** | UC06 - Nhận / từ chối chuyến | Từ chối hoặc không phản hồi thì hệ thống tìm tài xế khác. |
| **AC09** | UC07 - Thực hiện chuyến xe | Tài xế cập nhật trạng thái chuyến theo đúng trình tự. |
| **AC10** | UC08 - Theo dõi chuyến xe | Khách hàng xem được trạng thái hiện tại của chuyến xe. |
| **AC11** | UC09 - Tính cước | Hệ thống tính và hiển thị cước chuyến xe. |
| **AC12** | UC10 - Thanh toán | Khách hàng lựa chọn được phương thức thanh toán được hỗ trợ. |
| **AC13** | UC10 - Thanh toán | Thanh toán thành công thì hệ thống ghi nhận giao dịch thành công. |
| **AC14** | UC11 - Xử lý thanh toán thất bại | Thanh toán thất bại thì hệ thống thông báo và cho phép thanh toán lại theo chính sách. |
| **AC15** | UC12 - Đánh giá chuyến xe | Chỉ được đánh giá khi chuyến xe đã hoàn tất. |
| **AC16** | UC12 - Đánh giá chuyến xe | Hệ thống lưu điểm và nội dung đánh giá. |
| **AC17** | UC13 - Hoàn tất chuyến xe | Hệ thống chỉ xác nhận hoàn tất khi đáp ứng điều kiện cần thiết. |
| **AC18** | UC13 - Hoàn tất chuyến xe | Chuyến xe hoàn tất được lưu vào lịch sử. |
| **AC19** | UC14 - Quản lý khách hàng | Người có quyền có thể quản lý thông tin khách hàng. |
| **AC20** | UC15 - Quản lý tài xế | Người có quyền có thể quản lý thông tin tài xế. |
| **AC21** | UC16 - Quản lý phương tiện | Người có quyền có thể quản lý thông tin phương tiện. |
| **AC22** | UC17 - Theo dõi hoạt động vận hành | Nhân viên vận hành theo dõi được chuyến xe và tài xế. |
| **AC23** | UC18 - Quản lý tài khoản và phân quyền | Quản trị viên quản lý được tài khoản và phân quyền. |
| **AC24** | UC19 - Xem báo cáo thống kê | Người có quyền xem được các báo cáo thống kê của hệ thống. |

B14: BẢNG TRUY VẾT AC - ACCEPTANCE CRITERIA

| Mã UC | Tên Use Case | Mã AC | Acceptance Criteria |
|---|---|---|---|
| UC01 | Đăng nhập | AC01 | Đăng nhập thành công khi thông tin tài khoản hợp lệ |
| UC01 | Đăng nhập | AC02 | Hiển thị thông báo lỗi khi thông tin đăng nhập không hợp lệ |
| UC02 | Quản lý thông tin cá nhân | AC03 | Người dùng có thể xem và cập nhật thông tin cá nhân hợp lệ |
| UC03 | Đặt xe | AC04 | Đặt xe thành công khi nhập đầy đủ thông tin chuyến đi |
| UC03 | Đặt xe | AC05 | Hệ thống thông báo lỗi khi thông tin đặt xe không hợp lệ |
| UC04 | Tìm kiếm tài xế phù hợp | AC06 | Hệ thống tìm được tài xế đáp ứng điều kiện phục vụ chuyến đi |
| UC05 | Phân công tài xế | AC07 | Chuyến xe được gán cho tài xế khi tài xế chấp nhận |
| UC06 | Nhận / từ chối chuyến | AC08 | Tài xế có thể chấp nhận hoặc từ chối chuyến |
| UC06 | Nhận / từ chối chuyến | AC09 | Khi tài xế từ chối hoặc không phản hồi, hệ thống tiếp tục tìm tài xế khác |
| UC07 | Thực hiện chuyến xe | AC10 | Tài xế cập nhật được trạng thái chuyến theo đúng trình tự |
| UC08 | Theo dõi chuyến xe | AC11 | Khách hàng xem được trạng thái hiện tại của chuyến xe |
| UC09 | Tính cước chuyến xe | AC12 | Hệ thống tính và hiển thị cước chuyến xe |
| UC10 | Thanh toán chuyến xe | AC13 | Khách hàng lựa chọn được phương thức thanh toán |
| UC10 | Thanh toán chuyến xe | AC14 | Giao dịch được ghi nhận thành công khi thanh toán thành công |
| UC11 | Xử lý thanh toán thất bại | AC15 | Hệ thống thông báo khi thanh toán thất bại |
| UC11 | Xử lý thanh toán thất bại | AC16 | Khách hàng có thể thực hiện lại thanh toán theo chính sách |
| UC12 | Đánh giá chuyến xe | AC17 | Khách hàng chỉ được đánh giá sau khi chuyến xe hoàn tất |
| UC12 | Đánh giá chuyến xe | AC18 | Điểm đánh giá và nhận xét được lưu thành công |
| UC13 | Hoàn tất chuyến xe | AC19 | Chuyến xe chỉ được hoàn tất khi đáp ứng điều kiện hoàn thành |
| UC13 | Hoàn tất chuyến xe | AC20 | Thông tin chuyến xe được lưu vào lịch sử sau khi hoàn tất |
| UC14 | Quản lý khách hàng | AC21 | Nhân viên/Admin có thể xem và quản lý thông tin khách hàng theo quyền |
| UC15 | Quản lý tài xế | AC22 | Nhân viên/Admin có thể quản lý thông tin và trạng thái tài xế |
| UC16 | Quản lý phương tiện | AC23 | Nhân viên/Admin có thể quản lý thông tin phương tiện theo quyền |
| UC17 | Theo dõi hoạt động vận hành | AC24 | Nhân viên vận hành xem được các chuyến xe và trạng thái đang hoạt động |
| UC18 | Quản lý tài khoản và phân quyền | AC25 | Admin có thể quản lý tài khoản và phân quyền người dùng |
| UC19 | Xem báo cáo thống kê | AC26 | Nhân viên/Admin xem được các báo cáo thống kê theo dữ liệu hệ thống |
