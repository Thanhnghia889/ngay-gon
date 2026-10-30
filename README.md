# Ngày Gọn — lịch, ghi chú và báo thức

Ứng dụng Android tiếng Việt, dùng lịch/ghi chú/deadline và mic ngoại tuyến, không cần tài khoản.

**[Tải bản mới nhất](https://github.com/Thanhnghia889/ngay-gon/releases/latest)**

## Cài và cập nhật

1. Tải APK trong mục Releases và mở trên điện thoại Android 8 trở lên.
2. Nếu đã có bản cũ, cài đè để giữ dữ liệu. Không gỡ app trước khi cập nhật.
3. Từ bản 1.4.0, app có mục **Thông báo** (biểu tượng chuông). Khi có bản mới, chọn **Cập nhật** hoặc **Để sau**.
4. Bấm Cập nhật để app tự tải APK, kiểm tra tệp và mở trình cài đặt Android. Cho phép cài từ Ngày Gọn khi Android hỏi, rồi xác nhận cài bản mới.

Lịch, ghi chú, deadline và mic vẫn dùng offline. Chỉ kiểm tra/tải bản mới cần mạng. Cập nhật được kiểm tra định kỳ và khi mở app; Android có thể trì hoãn kiểm tra nền do tiết kiệm pin. App không gửi nội dung ghi chú hay âm thanh tới GitHub.

## Báo thức nền

Vào **Cài đặt → Chạy nền**, cho phép hoạt động nền, bật thông báo và Nhắc đúng giờ. Dùng **Thử khi đã đóng app** để thử chuông sau 60 giây. Lịch được khôi phục sau khi khởi động lại máy và mở khóa lần đầu. Force stop chặn hoạt động cho đến khi mở app lại; máy tắt nguồn không reo.

## Nhập bằng mic

Chọn **Nhập nhanh → Nói**, đọc ngày giờ và nội dung, bấm **Dừng**, kiểm tra chữ và kết quả rồi **Thêm lịch**. Ví dụ: “Ngày mai tám giờ ba mươi họp nhóm nhắc trước mười lăm phút”. Mic chỉ hoạt động sau khi bấm Nói; dừng khi đóng khung, rời app hoặc sau tối đa 60 giây. Không lưu bản ghi âm.

## Phạm vi kho này

Kho công khai này chỉ phát hành APK, thông tin cập nhật và hướng dẫn. Mã nguồn, dữ liệu cá nhân và khóa ký không lưu trong kho này. APK dùng Vosk và mô hình tiếng Việt theo Apache 2.0; thông báo giấy phép nằm trong APK tại assets/voice.

Đã kiểm tra trên máy ảo Android; cần thử quyền nền, chuông và độ chính xác mic trên điện thoại của bạn. Trước khi chuyển máy/gỡ ứng dụng, xuất bản sao lưu JSON trong Cài đặt.
