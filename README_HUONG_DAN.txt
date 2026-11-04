ỨNG DỤNG ANDROID: BÁO SĨ SỐ NẬM XE

Ứng dụng này là vỏ Android WebView mở hệ thống đang chạy tại:
https://bao-si-so-nam-xe.onrender.com/

Dữ liệu và tài khoản tiếp tục dùng chung trên máy chủ Render. APK không chứa bản sao cơ sở dữ liệu, không thay đổi mã nguồn Flask hoặc dữ liệu trên máy chủ.

CÁCH TẠO APK TỰ ĐỘNG
1. Giải nén thư mục dự án này.
2. Tạo một repository GitHub mới và tải toàn bộ nội dung thư mục lên (bao gồm thư mục .github).
3. Mở tab Actions của repository.
4. Chọn workflow “Build Android APK”, nhấn Run workflow.
5. Chờ workflow hoàn tất; mở lần chạy vừa xong, kéo xuống mục Artifacts.
6. Tải artifact “Bao-si-so-Nam-Xe-APK.zip”, giải nén sẽ có app-debug.apk.
7. Gửi app-debug.apk cho giáo viên. Trên Android, mở tệp APK và cho phép cài đặt ứng dụng từ nguồn này nếu điện thoại hỏi.

LƯU Ý
- Cần kết nối Internet để đăng nhập và báo sĩ số.
- Nếu Render đang ngủ, lần mở đầu có thể cần chờ máy chủ khởi động.
- Chỉ cài APK do repository của nhà trường tạo ra. Bản debug phù hợp triển khai nội bộ; không chia sẻ khóa ký hoặc mật khẩu quản trị qua nhóm chat.
