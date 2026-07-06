# 1. Tại sao trước khi bắt đầu một dự án, việc chọn kiến trúc lại là bước sống còn?

- ## Vì trước khi bắt đầu một dự án, nên xác định xem nên chọn kiến trúc nào cho phù hợp với các khả năng sau:

|      Khả năng      | Kiểm tra                                                                          |
|:------------------:|:----------------------------------------------------------------------------------|
|  Khả năng mở rộng  | Hệ thống có chịu tải được khi lượng người dùng tăng lên từ 100 lên 1 triệu không? |
|  Khả năng bảo trì  | Khi muốn sửa một tính năng, bạn có phải đập đi xây lại cả hệ thống không?         |
| Khả năng chịu lỗi  | Nếu một bộ phận bị hỏng, toàn bộ ứng dụng có bị "sập" theo không?                 |

## => Kiến trúc phần mềm không phải là chọn phương án tốt nhất, mà là chọn phương án phù hợp nhất. Một khi đã có kiến trúc tốt (phù hợp), không đảm bảo dự án sẽ thành công, nhưng nếu kiến trúc không tốt thì chắc chắn dự án sẽ thất bại!

# 2. Liệt kê các loại kiến trúc phần mềm mà bạn biết (Ít nhất 3 loại)?

 ## A. Kiến trúc Monolithic (Đơn khối)

 ## B. Kiến trúc Phân tầng (Layered Architecture)

 ## C. Kiến trúc Microservices (Vi dịch vụ)

# 3. Hãy liệt kê và giải thích các thuộc tính chất lượng (Quality Attributes) của phần mềm (Ví dụ: Scalability, Availability, Maintainability...)?

* ## Availability (Tính sẵn sàng): Thời gian hệ thống hoạt động bình thường (ví dụ: 99.99%).
* ## Reliability (Tính tin cậy): Khả năng thực hiện đúng chức năng trong điều kiện quy định.
* ## Security (Tính bảo mật): Bảo vệ dữ liệu và ngăn chặn tấn công.
* ## Deployability (Tính triển khai): Việc đưa code mới lên môi trường thật có dễ dàng và an toàn không?
