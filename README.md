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
## Xây dựng quy trình nghiệp vụ dựa trên Business Requirements

### 1. Mục đích

Quy trình nghiệp vụ của CAB System được xây dựng dựa trên các Business Requirements (BG) và Business Rules (BR) nhằm mô tả toàn bộ quá trình đặt và thực hiện chuyến xe.

Quy trình bắt đầu từ khi khách hàng tạo yêu cầu đặt xe, hệ thống tìm kiếm và phân công tài xế, thực hiện chuyến đi, tính cước, thanh toán và kết thúc bằng việc đánh giá dịch vụ.

### 2. Quy trình nghiệp vụ tổng quát

```text
Khách hàng
    |
    v
Tạo yêu cầu đặt xe
    |
    v
Kiểm tra thông tin đặt xe
    |
    v
Tìm kiếm tài xế phù hợp
    |
    v
Gửi yêu cầu nhận chuyến
    |
    v
Tài xế phản hồi
    |
    +------------------------+
    |                        |
 Chấp nhận              Từ chối/
    |                  Không phản hồi
    v                        |
Phân công tài xế             v
    |                  Tìm tài xế khác
    |                        |
    +<-----------------------+
    |
    v
Thông báo kết quả cho khách hàng
    |
    v
Tài xế đến điểm đón
    |
    v
Đón khách
    |
    v
Thực hiện chuyến đi
    |
    v
Hoàn thành chuyến
    |
    v
Tính cước
    |
    v
Thanh toán
    |
    +------------------------+
    |                        |
 Thành công              Thất bại
    |                        |
    v                        v
Ghi nhận giao dịch      Thông báo lỗi
    |                        |
    |                        v
    |                  Thực hiện lại
    |                  theo chính sách
    |                        |
    +-----------+------------+
                |
                v
        Khách hàng đánh giá
                |
                v
        Cập nhật báo cáo
                |
                v
        Kết thúc quy trình
```
### 3. Quy trình nghiệp vụ chi tiết

| STT | Hoạt động nghiệp vụ | Actor | Business Requirement | Business Rule | Kết quả |
|---:|---|---|---|---|---|
| 1 | Tạo yêu cầu đặt xe | Khách hàng | BG01 | BR01 | Yêu cầu đặt xe được tạo |
| 2 | Kiểm tra thông tin đặt xe | Hệ thống | BG01 | BR01 | Yêu cầu hợp lệ được tiếp tục xử lý |
| 3 | Tìm kiếm tài xế phù hợp | Hệ thống | BG02 | BR02 | Xác định được tài xế phù hợp |
| 4 | Gửi yêu cầu nhận chuyến | Hệ thống | BG02 | BR02 | Tài xế nhận được yêu cầu |
| 5 | Phản hồi yêu cầu chuyến | Tài xế | BG02 | BR02 | Xác định trạng thái nhận hoặc từ chối |
| 6 | Xử lý tài xế từ chối/không phản hồi | Hệ thống | BG02 | BR02 | Tiếp tục tìm tài xế khác |
| 7 | Phân công tài xế | Hệ thống | BG02 | BR02 | Tài xế được phân công |
| 8 | Thông báo kết quả phân công | Hệ thống | BG07 | BR07 | Khách hàng được thông báo |
| 9 | Di chuyển đến điểm đón | Tài xế | BG03 | BR03 | Trạng thái chuyến được cập nhật |
| 10 | Đón khách | Tài xế | BG03 | BR03 | Chuyến chuyển sang trạng thái đã đón khách |
| 11 | Thực hiện chuyến đi | Tài xế | BG03 | BR03 | Chuyến đang được thực hiện |
| 12 | Hoàn thành chuyến | Tài xế | BG03 | BR03 | Chuyến được ghi nhận hoàn thành |
| 13 | Tính cước | Hệ thống | BG05 | BR05 | Xác định số tiền cần thanh toán |
| 14 | Thực hiện thanh toán | Khách hàng | BG05 | BR05 | Yêu cầu thanh toán được xử lý |
| 15 | Kiểm tra kết quả thanh toán | Hệ thống | BG05 | BR05 | Xác định giao dịch thành công/thất bại |
| 16 | Xử lý thanh toán thất bại | Hệ thống | BG05 | BR05 | Thông báo lỗi và hỗ trợ thanh toán lại |
| 17 | Ghi nhận giao dịch | Hệ thống | BG04 | BR04 | Giao dịch được lưu trữ |
| 18 | Gửi thông báo hoàn thành | Hệ thống | BG07 | BR07 | Khách hàng nhận được thông báo |
| 19 | Đánh giá chuyến đi | Khách hàng | BG13 | BR12 | Đánh giá được ghi nhận |
| 20 | Cập nhật dữ liệu báo cáo | Hệ thống | BG12 | BR11 | Dữ liệu được cập nhật phục vụ báo cáo |
