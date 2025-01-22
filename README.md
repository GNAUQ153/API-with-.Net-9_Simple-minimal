# Minimal API with ASP.NET Core

## Tổng quan
# Dự án này xây dựng một API đơn giản bằng ASP.NET Core (.NET 9.0) để quản lý danh sách các công việc (to-do items). API này thực hiện các tác vụ CRUD (Create, Read, Update, Delete).
# Hơn nữa, dự án này phù hợp cho microservices và các ứng dụng nhỏ gọn.

### Các API được triển khai

| HTTP Method | Endpoint                | Mô tả                              | Request Body   | Response Body |
|-------------|-------------------------|-------------------------------------|----------------|---------------|
| GET         | `/todoitems`            | Lấy tất cả các công việc            | None           | Mảng công việc|
| GET         | `/todoitems/complete`   | Lấy các công việc đã hoàn thành     | None           | Mảng công việc|
| GET         | `/todoitems/{id}`       | Lấy công việc theo ID               | None           | Công việc      |
| POST        | `/todoitems`            | Thêm một công việc mới              | Công việc      | Công việc      |
| PUT         | `/todoitems/{id}`       | Cập nhật một công việc hiện có      | Công việc      | None          |
| DELETE      | `/todoitems/{id}`       | Xóa một công việc                   | None           | None          |

## Kết quả đạt được
# Phát triển một API tối giản với các thao tác CRUD.
# Tích hợp cơ sở dữ liệu trong bộ nhớ bằng Entity Framework Core.
# Đơn giản hóa quá trình phát triển API với cú pháp ngắn gọn.

## Nguồn tham khảo
[Microsoft Documentation: Minimal Web API](https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-9.0&tabs=visual-studio)
