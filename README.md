# postman

## Báo cáo bài tập thực hành kiểm thử API với Postman 
**Giới thiệu:** 
Bài tập thực hành này nhằm mục đích rèn luyện kỹ năng sử dụng Postman để thực hiện các thao tác kiểm thử API. 
Bài tập sử dụng bộ sưu tập Postman và các yêu cầu HTTP để kiểm tra API người dùng. 
**Nội dung:** 
### 3.1 Tạo bộ sưu tập Postman Tạo bộ sưu tập mới với tên "API Testing Practice". 
Thêm các yêu cầu HTTP sau vào bộ sưu tập: 
* * GET /users: Lấy danh sách người dùng.
* * POST /users: Tạo người dùng mới.
* * GET /users/:id: Lấy thông tin người dùng theo ID.
* * PUT /users/:id: Cập nhật thông tin người dùng.
* * DELETE /users/:id: Xóa người dùng.
* ### 3.2 Viết các yêu cầu

* Mục tiêu:

Viết các yêu cầu HTTP cho từng thao tác CRUD (Create, Read, Update, Delete) để kiểm thử API người dùng.
Sử dụng các biến để lưu trữ và truy cập dữ liệu một cách hiệu quả.
Xác minh tính hợp lệ của JSON bằng công cụ JSON validator trong Postman để đảm bảo dữ liệu được gửi và nhận chính xác.
Quy trình:

Tạo yêu cầu GET /users:

Mở bộ sưu tập Postman "API Testing Practice".
Nhấp vào nút "Add New Request" ở góc dưới bên trái màn hình.
Nhập "GET" vào trường "Method" và "https://api.example.com/users" vào trường "URL".
Chọn "JSON" trong phần "Body".
Nhấp vào nút "Send" để gửi yêu cầu.
Xác minh kết quả GET /users:

Kiểm tra mã trạng thái HTTP trong tab "Response". Mã trạng thái 200 cho biết yêu cầu thành công.
Xem nội dung phản hồi JSON trong tab "Body". Nội dung phản hồi JSON nên bao gồm danh sách người dùng.
Tạo yêu cầu POST /users:

Nhấp vào nút "New Request" và chọn "POST" làm phương thức.
Nhập "https://api.example.com/users" vào trường URL.
Chọn "JSON" trong phần Body.
Nhập dữ liệu người dùng mới vào Body JSON. Ví dụ:
JSON
{
  "name": "Jane Doe",
  "email": "janedoe@example.com",
  "age": 30
}

* Nhấp vào nút "Send" để gửi yêu cầu.
Xác minh kết quả POST /users:

Kiểm tra mã trạng thái HTTP. Mã trạng thái 201 cho biết người dùng mới đã được tạo thành công.
Xem nội dung phản hồi JSON. Nội dung phản hồi JSON nên bao gồm thông tin người dùng mới.
Tạo yêu cầu GET /users/:id:

Nhấp vào nút "New Request" và chọn "GET" làm phương thức.
Nhập "https://api.example.com/users/:id" vào trường URL.
Thay thế ":id" bằng ID của người dùng bạn muốn lấy thông tin.
Nhấp vào nút "Send" để gửi yêu cầu.
Xác minh kết quả GET /users/:id:

Kiểm tra mã trạng thái HTTP. Mã trạng thái 200 cho biết yêu cầu thành công.
Xem nội dung phản hồi JSON. Nội dung phản hồi JSON nên bao gồm thông tin của người dùng với ID đã cho.
Tạo yêu cầu PUT /users/:id:

Nhấp vào nút "New Request" và chọn "PUT" làm phương thức.
Nhập "https://api.example.com/users/:id" vào trường URL.
Thay thế ":id" bằng ID của người dùng bạn muốn cập nhật.
Chọn "JSON" trong phần Body.
Nhập dữ liệu người dùng đã cập nhật vào Body JSON. Ví dụ:
JSON
{
  "name": "Jane Doe",
  "email": "janedoe@example.com",
  "age": 35
}
* Nhấp vào nút "Send" để gửi yêu cầu.
Xác minh kết quả PUT /users/:id:

Kiểm tra mã trạng thái HTTP. Mã trạng thái 200 cho biết người dùng đã được cập nhật thành công.
Xem nội dung phản hồi JSON. Nội dung phản hồi JSON nên bao gồm thông tin người dùng đã cập nhật.
Tạo yêu cầu DELETE /users/:id:

Nhấp vào nút "New Request" và chọn "DELETE" làm phương thức.
Nhập "https://api.example.com/users/:id" vào trường URL.
Thay thế ":id" bằng ID của người dùng bạn muốn xóa.
Nhấp vào nút "Send" để gửi yêu cầu.
Xác minh kết quả DELETE /users/:id:

Kiểm tra mã trạng thái HTTP. Mã trạng thái 204 cho biết người dùng đã được xóa thành công.
Nội dung phản


  
### hình ảnh minh họa 

