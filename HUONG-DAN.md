# Ngày Gọn 1.4.0 — cập nhật trong app qua GitHub

## Cài lần đầu để bật chức năng cập nhật

Tải APK tại [GitHub Releases](https://github.com/Thanhnghia889/ngay-gon/releases/latest), mở trên điện thoại và cài đè bản cũ. Không gỡ app để giữ dữ liệu. Bản 1.3.0 chưa có chức năng này, nên cần cài bản 1.4.0 một lần; các bản tiếp theo cập nhật ngay trong app.

## Khi có bản mới

1. App hiện thông báo Android và chấm báo ở biểu tượng chuông **Thông báo** trong app.
2. Chọn **Cập nhật** để tải APK từ GitHub. Tiến độ tải hiện trong app và thông báo Android; có thể đóng app, tải vẫn do DownloadManager của Android quản lý.
3. App kiểm tra SHA-256, kích thước, mã gói, phiên bản và khóa ký. Chỉ chấp nhận APK mới hơn, cùng khóa ký.
4. Khi tải xong và vẫn ở màn hình cập nhật, app tự mở bước cài đặt. Nếu đã rời app, chạm thông báo Đã tải xong hoặc vào Thông báo → Cài đặt bản mới.
5. Nếu Android hỏi, cho phép cài từ Ngày Gọn, quay lại và xác nhận **Update / Cập nhật**. Play Protect có thể yêu cầu quét APK; đọc thông báo và lựa chọn trên màn hình Android. App không bỏ qua được quyết định của hệ điều hành.

Chọn **Để sau** để tiếp tục dùng bình thường. Bản mới hoặc bản đã tải vẫn nằm trong mục Thông báo; không phải tìm lại file APK. Chỉ báo một lần cho mỗi phiên bản để tránh làm phiền, ngoài thông báo tải xong.

Nếu hệ thống từ chối ở bước xác minh, app hiển thị lý do và giữ bản tải để thử lại. Không cần gỡ app. Một số thiết bị/khu vực có yêu cầu xác minh nhà phát triển riêng; GitHub không thay thế yêu cầu đó của Android.

## Thời điểm thông báo

Khi mở app, tự kiểm tra nếu lần thử trước cách ít nhất 1 giờ. Kiểm tra nền được lên lịch khoảng mỗi 24 giờ và cần mạng; Android có thể trì hoãn theo pin, kết nối và trạng thái thiết bị. Không phải thông báo tức thì ngay khi phát hành. Có nút **Kiểm tra bản cập nhật** để kiểm tra ngay.

Thông báo Android cần được cấp quyền và kênh Cập nhật ứng dụng cần bật. Nếu thông báo bị tắt, vẫn xem được bản mới trong app. Khi Force stop, Android dừng tác vụ nền cho đến khi mở app lại.

## Offline, dữ liệu và dung lượng

- Lịch, ghi chú, deadline, chuông và mic tiếng Việt tiếp tục chạy offline, không cần tài khoản.
- Từ 1.4.0, app có quyền INTERNET chỉ để kiểm tra thông tin bản mới và tải APK từ GitHub. Không gửi nội dung lịch, ghi chú hoặc âm thanh tới GitHub. GitHub vẫn nhận thông tin kết nối như địa chỉ IP và phiên bản app trong yêu cầu tải/kiểm tra.
- Mỗi lần cập nhật tải APK đầy đủ, hiện khoảng 48 MB; cần thêm chỗ trống để Android chuẩn bị cài. Chưa có cập nhật phần chênh lệch.
- Cài đè cùng mã ứng dụng/khóa ký giữ cơ sở dữ liệu hiện tại. Có thể xuất sao lưu JSON trước khi cập nhật hoặc đổi máy.
- APK và hướng dẫn là công khai trên GitHub, ai có link cũng tải được. Mã nguồn và khóa ký được giữ riêng. APK vẫn có thể được phân tích/dịch ngược như các ứng dụng Android khác.

## Giới hạn cần biết

Android vẫn có thể yêu cầu xác nhận cài đặt và quét bảo mật, hoặc chặn theo chính sách thiết bị/xác minh nhà phát triển. Cập nhật cần GitHub hoạt động và điện thoại có mạng; mất mạng không ảnh hưởng chức năng lịch, ghi chú hoặc mic. Thông báo nền có thể trễ. Mất khóa ký sẽ gây khó khăn cho việc cập nhật giữ dữ liệu, nên khóa ký được giữ riêng, không đưa lên GitHub.

Đã thử cập nhật qua GitHub và trình cài đặt/Play Protect trên máy ảo Android, giữ được ghi chú trước cập nhật. Chưa kiểm tra mọi điện thoại/hãng máy.
