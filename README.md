# TỔNG HỢP CÁC THUẬT NGỮ MÀ IT BA/PO CẦN BIẾT  📘

Đây là những thuật ngữ nền tảng mà bất kỳ **Business Analyst (BA)** hay **Product Owner (PO)** nào cũng cần nắm vững để làm việc hiệu quả với team kỹ thuật, khách hàng và các bên liên quan trong dự án phần mềm.

---
### **1. BRD – Business Requirements Document**

**Định nghĩa:**
BRD là tài liệu mô tả **yêu cầu nghiệp vụ (Business Requirements)** và mong đợi của **các bên liên quan (Stakeholders)** trong dự án.

**Mục đích:**

* Xác định *“vấn đề cần giải quyết”* ở cấp độ kinh doanh.
* Đảm bảo tất cả các bên hiểu thống nhất về mục tiêu và phạm vi dự án.

**Ví dụ:**
BRD cho hệ thống đặt phòng có thể mô tả:

> “Khách hàng cần có khả năng tìm kiếm và đặt phòng trọ theo vị trí, giá và tiện nghi.”

---
### **2. SRS – Software Requirements Specification**

**Định nghĩa:**
SRS là tài liệu **đặc tả yêu cầu phần mềm**, mô tả chi tiết tất cả yêu cầu **chức năng**, **phi chức năng**, và **dữ liệu** của hệ thống.

**Vai trò:**

* Là cầu nối giữa **BA/PO, Developer và QA**.
* Là cơ sở cho việc thiết kế, phát triển và kiểm thử phần mềm.

**Ví dụ:**
Mục “Đăng ký tài khoản” trong SRS có thể nêu rõ:

> Trường bắt buộc: Email, Password.
> Validation: Email phải đúng định dạng, Password ≥ 8 ký tự.

---
### **3. BPMN – Business Process Model and Notation**

**Định nghĩa:**
BPMN là ngôn ngữ **mô hình hóa quy trình nghiệp vụ** bằng các ký hiệu chuẩn quốc tế.

**Mục đích:**

* Giúp các bên (BA, Dev, QA, Stakeholder) hiểu thống nhất về **luồng xử lý nghiệp vụ**.
* Hỗ trợ **phân tích, tối ưu và tự động hóa quy trình**.

**Ví dụ:**
Sơ đồ BPMN cho “Đặt phòng” gồm các bước:
**Khách hàng → Gửi yêu cầu → Hệ thống kiểm tra phòng → Xác nhận → Thanh toán.**

---
### **4. Stakeholder**

**Định nghĩa:**
Stakeholder là **bất kỳ cá nhân, nhóm hoặc tổ chức** nào bị ảnh hưởng bởi kết quả dự án hoặc có ảnh hưởng đến nó.

**Ví dụ:**
Trong dự án đặt phòng:

* **Khách hàng:** Người thuê phòng
* **Host:** Chủ nhà
* **Admin:** Quản trị viên hệ thống
* **PO, DEV, QA:** Nội bộ phát triển sản phẩm

**Vai trò:**
Stakeholders là người **cung cấp yêu cầu**, **đánh giá kết quả**, và **tác động đến thành công của dự án**.

---
### **5. Scope – Phạm vi dự án**

**Định nghĩa:**
Scope là **giới hạn công việc** của dự án — xác định **những gì nằm trong và ngoài phạm vi** phát triển.

**Ví dụ:**

> ✅ Trong phạm vi: Chức năng đặt phòng, hủy phòng.
> ❌ Ngoài phạm vi: Thanh toán qua thẻ quốc tế (được xem xét ở phase sau).

**Mục đích:**
Giúp tránh **“scope creep”** – tức là mở rộng yêu cầu ngoài kế hoạch khiến dự án trễ và vượt chi phí.

---
### **6. CRUD – Create, Read, Update, Delete**

**Định nghĩa:**
CRUD là **bốn hành động cơ bản** để thao tác dữ liệu trong bất kỳ hệ thống phần mềm nào.

**Ví dụ:**

* **Create:** Thêm mới phòng trọ
* **Read:** Xem danh sách phòng
* **Update:** Cập nhật giá phòng
* **Delete:** Xóa thông tin phòng

**Ứng dụng:**
Hiểu CRUD giúp BA viết **Use Case** và xác định logic dữ liệu cho từng chức năng.

---
### **7. Domain – Miền nghiệp vụ**

**Định nghĩa:**
Domain là **lĩnh vực chuyên môn hoặc phạm vi nghiệp vụ** mà hệ thống hoạt động trong đó.

**Ví dụ:**

* Hệ thống ngân hàng → Domain: Tài chính, tín dụng
* Hệ thống đặt phòng → Domain: Hospitality, booking

**Lợi ích:**
Nắm vững domain giúp BA **hiểu rõ thuật ngữ, quy trình và ràng buộc nghiệp vụ**, từ đó đặc tả chính xác yêu cầu.

---
### **8. Wireframe**

**Định nghĩa:**
Wireframe là **bản phác thảo khung giao diện (UI skeleton)** — mô tả bố cục, vị trí thành phần, nhưng **chưa có màu sắc hoặc chi tiết thiết kế**.

**Mục đích:**

* Truyền đạt nhanh **ý tưởng cấu trúc màn hình**.
* Làm cơ sở để team UI/UX và Developer thảo luận trước khi thiết kế chi tiết.

**Ví dụ:**
Wireframe cho màn hình “Đăng ký” gồm các thành phần:

* Logo
* Form Email/Password
* Nút “Đăng ký”

---
### **9. Mockup**

**Định nghĩa:**
Mockup là **phiên bản trực quan nâng cấp** của wireframe — có màu sắc, font chữ, logo và nhận diện thương hiệu.

**Mục đích:**

* Giúp Stakeholder **hình dung sản phẩm gần với thực tế**.
* Dùng để **review về mặt thẩm mỹ, UX/UI** trước khi xây dựng prototype.

**Lưu ý:**
Mockup **không có chức năng tương tác**, chỉ thể hiện **giao diện tĩnh**.

---
### **10. Prototype**

**Định nghĩa:**
Prototype là **bản mẫu tương tác (interactive prototype)** mô phỏng gần như hoàn chỉnh **trải nghiệm thực tế của sản phẩm**.

**Vai trò:**

* Cho phép test **luồng thao tác người dùng (User Flow)**.
* Giúp đội dev hiểu rõ **cách hoạt động mong muốn** trước khi coding.

**Ví dụ:**
Prototype trong Figma có thể cho phép click qua các màn hình: **Trang chủ → Tìm phòng → Xem chi tiết → Thanh toán.**

---
### 🎯 **Kết luận**

Những khái niệm này là **“nền móng”** trong mọi dự án phần mềm.
Hiểu rõ chúng giúp BA/PO:
* Tránh hiểu sai yêu cầu
* Dẫn dắt quy trình từ **ý tưởng → đặc tả → sản phẩm mẫu → triển khai thực tế**

---

## 📉 CÁC THUẬT NGỮ KHI LÀM VIỆC VỚI BACKLOG VÀ PLAN
Công việc của một BA hay PO không chỉ là phân tích và nghiên cứu sản phẩm và còn cần làm những việc lập kế hoạch ngắn hạn và dài hạn cho dự án. Những thuật ngữ này sẽ cho bạn thông tin cần thiết để giao tiếp dễ dàng hơn với team của mình, đặc biệt là các bạn đang ở các cấp tiếp cặn hoặc thực tập. 

---
### **1. User Story**

**Định nghĩa:**
User Story là mô tả ngắn gọn về một tính năng từ góc nhìn của người dùng cuối.
Cấu trúc thường theo format:

> **As a [user], I want [goal] so that [reason].**

👉 **Ví dụ:**
*As a customer, I want to reset my password so that I can regain access to my account.*

**Ý nghĩa:**
User Story giúp đội phát triển tập trung đúng nhu cầu người dùng thay vì sa đà vào chi tiết kỹ thuật.

---
### **2. Epic**

**Định nghĩa:**
Epic là một nhóm các **User Story** có liên quan, thể hiện một phần chức năng lớn của sản phẩm.
Epic thường quá lớn để hoàn thành trong một Sprint, nên sẽ được chia nhỏ thành nhiều User Story.

👉 **Ví dụ:**
Epic **“Quản lý tài khoản người dùng”** có thể bao gồm các User Story như:

* Đăng ký tài khoản
* Đăng nhập
* Quên mật khẩu

---
### **3. Sprint**

**Định nghĩa:**
Sprint là chu kỳ phát triển ngắn (thường từ **1–4 tuần**), trong đó đội Scrum hoàn thành một khối lượng công việc cụ thể đã cam kết.

**Hoạt động chính:**

* **Sprint Review:** Trình bày (demo) sản phẩm hoàn thiện.
* **Sprint Retrospective:** Xem lại quy trình, rút kinh nghiệm và cải tiến.

---
### **4. Backlog Grooming (Refinement)**

**Định nghĩa:**
Là hoạt động **rà soát Product Backlog** để đảm bảo các User Story:

* Rõ ràng, có tiêu chí chấp nhận cụ thể
* Được ưu tiên hợp lý
* Sẵn sàng cho **Sprint Planning**

**Lợi ích:**
Giúp tiết kiệm thời gian lập kế hoạch và nâng cao hiệu quả làm việc nhóm.

---
### **5. MVP – Minimum Viable Product**

**Định nghĩa:**
MVP là **phiên bản nhỏ nhất của sản phẩm** có thể hoạt động được, đủ mang lại giá trị cho người dùng và thu thập phản hồi sớm.

👉 **Ví dụ:**
Thay vì xây cả hệ thống e-commerce hoàn chỉnh, **MVP** có thể chỉ bao gồm:

* Giỏ hàng cơ bản
* Trang thanh toán
* Quản lý tồn kho

---
### **6. Product Roadmap**

**Định nghĩa:**
Là **lộ trình phát triển sản phẩm**, thể hiện:

* Mục tiêu chính
* Các mốc thời gian
* Hướng phát triển sắp tới

**Mục đích:**
Giúp đội ngũ **đồng bộ (align)** với mục tiêu dài hạn và chiến lược chung.

---
### **7. Definition of Done (DoD)**

**Định nghĩa:**
Là **tiêu chuẩn hoàn thành** mà một User Story hoặc tính năng phải đạt để được coi là “Done”.

👉 **Ví dụ:**

> Code đã review xong, QA test pass, tài liệu hướng dẫn (user guide) được cập nhật.

**Lợi ích:**
Giảm hiểu lầm giữa BA, PO và Developer về tình trạng hoàn thành công việc.

---
### **8. Burn Down Chart**

**Định nghĩa:**
Biểu đồ thể hiện **lượng công việc còn lại so với thời gian Sprint**.

**Mục đích:**
Giúp PO và team:

* Theo dõi tiến độ Sprint
* Phát hiện sớm rủi ro chậm tiến độ

---
### **9. Acceptance Test**

**Định nghĩa:**
Là các bài **kiểm thử mô phỏng kịch bản thực tế** để xác minh tính năng đáp ứng đúng yêu cầu business và **Acceptance Criteria**.

**Thực hiện bởi:**
BA/PO phối hợp cùng QA trong giai đoạn kiểm thử chấp nhận.

---
### **10. Change Request**

**Định nghĩa:**
Là yêu cầu thay đổi tính năng hoặc phạm vi dự án từ **Stakeholder** trong quá trình phát triển.

**Vai trò của BA/PO:**

* Phân tích tác động (**Impact Analysis**)
* Đề xuất chấp nhận hoặc từ chối
* Đảm bảo không ảnh hưởng tiêu cực đến tiến độ hoặc ngân sách

---
### 🎯 **Ghi nhớ**

BA/PO không chỉ cần **biết** mà phải **hiểu sâu** những thuật ngữ này để:

* Giao tiếp hiệu quả với Developer, Tester, Designer và Stakeholder
* Đảm bảo sản phẩm phát triển đúng hướng và chất lượng

---

## ⚙️ **CÁC YÊU CẦU PHI CHỨC NĂNG (NON-FUNCTIONAL REQUIREMENTS)**

Bên cạnh các yêu cầu chức năng (Functional Requirements), một dự án chuyên nghiệp cần xác định rõ **các yêu cầu phi chức năng** để đảm bảo hệ thống hoạt động ổn định, an toàn và có khả năng mở rộng trong tương lai.

---
### **1. Security (Bảo mật)**
**Định nghĩa:**
Yêu cầu về bảo mật đề cập đến việc **bảo vệ dữ liệu và tài nguyên** khỏi truy cập trái phép, xâm nhập dữ liệu hoặc các mối đe dọa an ninh mạng.

**Ví dụ:**

* Hệ thống phải sử dụng cơ chế **mã hóa dữ liệu (Encryption)** cho thông tin nhạy cảm.
* Người dùng phải xác thực qua **OTP hoặc OAuth2** trước khi truy cập khu vực quản trị.
* Tất cả hoạt động đăng nhập và thao tác quan trọng cần được **ghi log và giám sát**.

---
### **2. Scalability (Khả năng mở rộng)**

**Định nghĩa:**
Yêu cầu về khả năng mở rộng xác định cách hệ thống **đáp ứng khi tải tăng lên**, ví dụ: thêm người dùng, dữ liệu hoặc giao dịch.

**Phân loại:**

* **Mở rộng ngang (Horizontal scaling):** Thêm máy chủ mới vào hệ thống.
* **Mở rộng dọc (Vertical scaling):** Nâng cấp tài nguyên phần cứng (CPU, RAM).

**Ví dụ:**
Hệ thống có thể mở rộng để xử lý **gấp 3 lần lượng người dùng hiện tại** mà không làm giảm hiệu năng.

---
### **3. Usability (Khả năng sử dụng)**

**Định nghĩa:**
Tập trung vào **trải nghiệm người dùng (UX)** và **thiết kế giao diện (UI)**, đảm bảo người dùng có thể thao tác dễ dàng và hiệu quả.

**Ví dụ:**

* Các nút và biểu tượng hiển thị rõ ràng, thống nhất.
* Có hướng dẫn sử dụng hoặc video tutorial cho người mới.
* Đáp ứng tiêu chuẩn **Accessibility (WCAG)** để hỗ trợ người dùng khuyết tật.

---
### **4. Compatibility (Tương thích)**

**Định nghĩa:**
Đảm bảo hệ thống **hoạt động ổn định trên nhiều nền tảng** — bao gồm hệ điều hành, trình duyệt, thiết bị và thành phần phần mềm khác.

**Ví dụ:**

* Hỗ trợ trình duyệt **Chrome, Firefox, Safari, Edge** (phiên bản mới nhất).
* Ứng dụng mobile tương thích với **iOS 13+ và Android 10+**.
* Tích hợp mượt mà với **API của bên thứ ba** mà không xung đột định dạng dữ liệu.

---
### **5. Maintainability (Khả năng bảo trì)**

**Định nghĩa:**
Đề cập đến **khả năng bảo trì, cập nhật và mở rộng hệ thống** trong tương lai mà không ảnh hưởng đến các module hiện có.

**Ví dụ:**

* Code phải được viết theo **chuẩn coding convention** và có comment đầy đủ.
* Kiến trúc hệ thống được **mô-đun hóa** để dễ dàng thay thế hoặc nâng cấp.
* Có **tài liệu hướng dẫn kỹ thuật (Technical Manual)** cho đội vận hành.

---
### **6. Compliance (Tuân thủ)**

**Định nghĩa:**
Liên quan đến việc **tuân thủ các quy định pháp luật, tiêu chuẩn ngành hoặc chính sách nội bộ** của tổ chức.

**Ví dụ:**

* Tuân thủ quy định **GDPR** về bảo vệ dữ liệu người dùng tại EU.
* Tuân thủ tiêu chuẩn **ISO/IEC 27001** về quản lý an ninh thông tin.
* Mã hóa dữ liệu nhạy cảm theo chuẩn **AES-256 hoặc TLS 1.3**.

---
### **7. Performance (Hiệu suất)**

**Định nghĩa:**
Xác định **hiệu năng và khả năng đáp ứng** của hệ thống trong các điều kiện sử dụng khác nhau.

**Ví dụ:**

* Thời gian phản hồi API < **200 ms** trong điều kiện tải trung bình.
* Trang web tải trong **< 3 giây** với tốc độ mạng trung bình.
* Hệ thống chịu được **10.000 người dùng đồng thời** mà không lỗi.

---
### **8. Safety (An toàn)**

**Định nghĩa:**
Đặc biệt quan trọng đối với các hệ thống **liên quan đến tính mạng, sức khỏe hoặc môi trường**, đảm bảo hành vi của hệ thống không gây rủi ro.

**Ví dụ:**

* Ứng dụng thiết bị y tế phải có cơ chế **fail-safe** khi mất kết nối.
* Giao dịch tài chính phải có **rollback** khi xảy ra lỗi hệ thống.
* Log sự cố phải được lưu trữ an toàn để phục vụ kiểm tra.

---
### **9. Interoperability (Khả năng tương tác)**

**Định nghĩa:**
Đề cập đến khả năng **trao đổi dữ liệu và phối hợp hoạt động** giữa hệ thống với các nền tảng khác.

**Ví dụ:**

* Hệ thống có thể tích hợp với **CRM, ERP, Payment Gateway**.
* Hỗ trợ **RESTful API** và định dạng dữ liệu **JSON/XML**.
* Đồng bộ dữ liệu hai chiều giữa các module nội bộ.

---
### **10. Capacity (Dung lượng hệ thống)**

**Định nghĩa:**
Xác định **giới hạn và ngưỡng tài nguyên** mà hệ thống có thể đáp ứng, bao gồm lưu trữ, bộ nhớ, băng thông và người dùng.

**Ví dụ:**

* Cơ sở dữ liệu hỗ trợ **tối đa 500 GB dữ liệu**.
* Server có thể phục vụ **20.000 request/giờ** mà không quá tải.
* Giới hạn tải lên mỗi tệp tối đa **50 MB**.

---
### **11. Localization & Internationalization (Đa ngôn ngữ & Đa vùng)**

**Định nghĩa:**
Áp dụng cho hệ thống phục vụ **người dùng toàn cầu**, đảm bảo hỗ trợ nhiều **ngôn ngữ, múi giờ và định dạng dữ liệu địa phương**.

**Ví dụ:**

* Giao diện hỗ trợ **tiếng Việt, tiếng Anh và tiếng Nhật**.
* Hiển thị **định dạng tiền tệ, ngày giờ** theo quốc gia.
* Cấu trúc nội dung và font chữ tương thích với các ký tự đặc biệt (UTF-8).

---
### 🎯 **Tổng kết**

Các yêu cầu phi chức năng không chỉ quyết định **hiệu suất và độ ổn định** của hệ thống, mà còn ảnh hưởng trực tiếp đến **trải nghiệm người dùng, khả năng vận hành và mở rộng lâu dài**.
Việc định nghĩa rõ ràng các yêu cầu này ngay từ đầu giúp giảm thiểu rủi ro và chi phí bảo trì trong tương lai.

