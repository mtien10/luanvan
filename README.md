# College-ERP
Hệ thống quản lý trường cao đẳng được xây dựng bằng cách sử dụng khuôn khổ Django. Nó được thiết kế để tương tác giữa học sinh và giáo viên. Các tính năng bao gồm điểm danh, điểm và bảng chấm công.
## Installation

Python and Django need to be installed

```bash
pip install django
```

## Usage

Go to the College-ERP folder and run

```bash
python manage.py runserver
```

Then go to the browser and enter the url **http://127.0.0.1:8000/**
## Login

Đăng nhập cho sinh viên và giáo viên
Mật khẩu mọi người  'project123'.  

Example usernames:  
student- 'caohuyen'  
teacher- 'manhtien'  

You can access the django admin page at **http://127.0.0.1:8000/admin** and login with username 'admin' and the above password.

Also a new admin user can be created using

```bash
python manage.py createsuperuser
```
Sinh viên và giáo viên mới có thể được thêm thông qua trang quản trị. Một người dùng mới cần được tạo cho mỗi.

Trang quản trị được sử dụng để sửa đổi tất cả các bảng như Sinh viên, Giáo viên, Phòng ban, Khóa học, Lớp học, v.v.

** Để biết thêm chi tiết về hệ thống và các tính năng, vui lòng tham khảo các báo cáo đi kèm. **
