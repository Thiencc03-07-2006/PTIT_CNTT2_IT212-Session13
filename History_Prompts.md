
# Prompt 1 - Khởi tạo dự án

```text
Bạn là một IT Consultant, Business Analyst và Senior System Analyst có hơn 15 năm kinh nghiệm.

Tôi cần xây dựng tài liệu Software Requirements Specification (SRS) theo chuẩn IEEE cho dự án "Hotel Management System".

Yêu cầu:

- Không viết tắt nội dung.
- Thiết kế hệ thống thực tế.
- Có ít nhất 3 Actors.
- Có ít nhất 3 Module.
- Có khả năng mở rộng.
- Phù hợp để phát triển bằng Spring Boot + MySQL + React.

Trước tiên hãy phân tích nghiệp vụ và đề xuất:

1. Mục tiêu hệ thống
2. Phạm vi hệ thống
3. Các Actors
4. Các Modules
5. Luồng nghiệp vụ tổng quan

Chưa viết SRS.
```

---

# Prompt 2 - Bổ sung Actors

```text
Hãy xem lại phần Actors.

Nếu còn thiếu actor quan trọng của một hệ thống quản lý khách sạn thực tế thì hãy bổ sung.

Đối với mỗi actor hãy mô tả:

- Vai trò
- Quyền hạn
- Các chức năng được phép sử dụng

Không bỏ sót nghiệp vụ.
```

---

# Prompt 3 - Hoàn thiện Modules

```text
Dựa trên các actors vừa xây dựng, hãy thiết kế lại toàn bộ modules.

Mỗi module cần có:

- Mục tiêu
- Chức năng
- Input
- Output
- Các nghiệp vụ xử lý

Đảm bảo tối thiểu gồm:

- Booking Management
- Room Management
- Customer Management

Nếu cần hãy bổ sung thêm module khác để hệ thống hoàn chỉnh.
```

---

# Prompt 4 - Functional Requirements

```text
Hãy viết Functional Requirements theo chuẩn IEEE.

Mỗi chức năng cần có:

- ID (FR-001...)
- Tên chức năng
- Mô tả
- Actor
- Điều kiện trước
- Luồng xử lý
- Điều kiện sau

Đảm bảo bao phủ toàn bộ nghiệp vụ.
```

---

# Prompt 5 - User Stories

```text
Dựa trên Functional Requirements, hãy viết đầy đủ User Stories.

Mỗi User Story theo mẫu:

As a ...
I want ...
So that ...

Sau mỗi User Story hãy bổ sung:

- Acceptance Criteria

Không bỏ sót actor nào.
```

---

# Prompt 6 - Non Functional Requirements

```text
Hãy xây dựng phần Non Functional Requirements.

Bao gồm:

- Performance
- Scalability
- Availability
- Security
- Backup
- Logging
- Audit
- Maintainability
- Portability
- Reliability
- Usability

Viết theo chuẩn SRS.
```

---

# Prompt 7 - Use Case

```text
Hãy xây dựng Use Case Diagram bằng Mermaid.

Yêu cầu:

- Hiển thị đầy đủ actors.
- Hiển thị đầy đủ use cases.
- Có include và extend nếu cần.
- Không để sơ đồ bị rối.
```

---

# Prompt 8 - Use Case Review

```text
Hãy đóng vai Senior Software Architect.

Review sơ đồ Use Case vừa tạo.

Nếu phát hiện:

- thiếu actor
- thiếu use case
- quan hệ sai
- include/extend chưa hợp lý

thì hãy sửa lại toàn bộ sơ đồ Mermaid.
```

---

# Prompt 9 - ERD

```text
Thiết kế cơ sở dữ liệu cho Hotel Management System.

Yêu cầu:

- Chuẩn hóa đến 3NF
- Có Primary Key
- Foreign Key
- Data Type
- Constraints

Sau đó sinh ER Diagram bằng Mermaid.
```

---

# Prompt 10 - Review Database

```text
Hãy review thiết kế database.

Kiểm tra:

- Quan hệ 1-N
- Quan hệ N-N
- Khóa ngoại
- Thiếu bảng
- Thiếu thuộc tính
- Thiếu trạng thái

Nếu phát hiện vấn đề hãy sửa lại toàn bộ ERD.
```

---

# Prompt 11 - Activity Diagram

```text
Hãy tạo Activity Diagram bằng Mermaid cho quy trình:

Khách hàng đặt phòng.

Bao gồm:

- Kiểm tra phòng
- Chọn phòng
- Thanh toán
- Xác nhận
- Gửi email

Đảm bảo đúng UML.
```

---

# Prompt 12 - Sequence Diagram

```text
Hãy xây dựng Sequence Diagram bằng Mermaid cho quy trình Booking.

Đối tượng gồm:

Customer
Frontend
Booking API
Database
Payment Gateway
Notification Service

Không bỏ sót bước nào.
```

---

# Prompt 13 - Class Diagram

```text
Hãy xây dựng Class Diagram bằng Mermaid.

Bao gồm:

- Entity
- Service
- Repository

Thể hiện đúng quan hệ kế thừa, association và composition nếu có.
```

---

# Prompt 14 - Kiểm tra toàn bộ SRS

```text
Bạn hãy đóng vai người chấm đồ án môn Phân tích thiết kế hệ thống.

Review toàn bộ tài liệu SRS.

Kiểm tra:

- Thiếu chức năng
- Thiếu actors
- Thiếu modules
- Thiếu user stories
- Thiếu yêu cầu phi chức năng
- Sai logic nghiệp vụ
- Sai ERD
- Sai Use Case

Liệt kê tất cả lỗi và sửa trực tiếp.
```

---

# Prompt 15 - Xuất tài liệu hoàn chỉnh

```text
Hãy tổng hợp toàn bộ nội dung đã xây dựng thành tài liệu Software Requirements Specification (SRS) hoàn chỉnh theo chuẩn IEEE.

Cấu trúc gồm:

1. Introduction
- Purpose
- Scope
- Definitions
- References

2. Overall Description
- Product Perspective
- Product Functions
- User Classes
- Operating Environment
- Constraints
- Assumptions

3. Functional Requirements

4. Non Functional Requirements

5. User Stories

6. Use Case Diagram

7. Activity Diagram

8. Sequence Diagram

9. Class Diagram

10. Database Design

11. ER Diagram

12. Business Rules

13. Future Enhancement

Không viết lời mở đầu như:
"Here is your document"
"I hope this helps"

Chỉ xuất nội dung tài liệu SRS.
```