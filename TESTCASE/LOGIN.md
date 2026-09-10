Test Case ID	Test Case Name	Điều kiện tiên quyết	Dữ liệu kiểm thử	Các bước thực hiện	Kết quả mong đợi	Mức độ ưu tiên
TC01	Successful Registration	Khách hàng chưa có tài khoản	Họ tên, số điện thoại, email, mật khẩu hợp lệ	1. Mở chức năng đăng ký.
2. Nhập đầy đủ thông tin hợp lệ.
3. Nhấn Đăng ký.	Hệ thống tạo tài khoản thành công.	Cao
TC02	Duplicate Email Registration	Email đã tồn tại trong hệ thống	Email đã đăng ký	1. Mở chức năng đăng ký.
2. Nhập email đã tồn tại.
3. Nhấn Đăng ký.	Hệ thống thông báo email đã tồn tại và không tạo tài khoản mới.	Cao
TC03	Missing Registration Information	Chưa nhập đầy đủ thông tin	Bỏ trống email hoặc mật khẩu	1. Nhập thiếu thông tin.
2. Nhấn Đăng ký.	Hệ thống yêu cầu nhập đầy đủ thông tin và không tạo tài khoản.	Cao
TC04	Successful Login	Tài khoản khách hàng đã tồn tại và đã xác thực	Email và mật khẩu hợp lệ	1. Nhập email.
2. Nhập mật khẩu.
3. Nhấn Đăng nhập.	Khách hàng đăng nhập thành công.	Cao
TC05	Incorrect Password Login	Tài khoản đã tồn tại	Email đúng, mật khẩu sai	1. Nhập email.
2. Nhập mật khẩu sai.
3. Nhấn Đăng nhập.	Hệ thống thông báo thông tin đăng nhập không chính xác và không cho đăng nhập.	Cao
TC06	Unauthenticated Booking	Khách hàng chưa đăng nhập/xác thực	Yêu cầu đặt xe	1. Truy cập chức năng đặt xe khi chưa đăng nhập.
2. Thực hiện yêu cầu đặt xe.	Hệ thống từ chối thao tác và yêu cầu đăng nhập/xác thực.	Cao
