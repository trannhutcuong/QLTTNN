Backend: yêu cầu cài đặt Nodejs, cài đặt xampp hoặc các ứng dụng khác để chạy mysql
import file QLTTNN.sql vào database (file trong thư mục ScriptDatabase)

Install: cd Backend -> npm install 

Danh sách các API hiện có:
localhost:3001/course -> Lấy danh sách các khóa học
	      /employee -> Lấy danh sách quản lý và giáo viên
	      /manager -> Lấy danh sách quản lý và giáo viên (quản lý quản lý các giáo viên 1-n)
	      /student -> Lấy danh sách học sinh
	      /notification -> Lấy danh sách các thông báo

Chạy 2 server DAL vs BUS:
cd Backend/BUS -> node app
cd Backend/DAL -> node app