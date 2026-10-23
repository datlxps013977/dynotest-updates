# DynoTest DATNL — Updates

Kênh cập nhật công khai chính thức. Source code được giữ trong repo riêng tư.

## Bản hiện tại: ver1.1.31

- RPM/SPEED chỉ ghi khi đạt MIN và tăng tốc trở lại; đang thòng ga vẫn chờ dù trên MIN.
- Xác nhận ít nhất 3 mẫu tăng trong tối thiểu 100 ms, tổng tăng 50 RPM hoặc 0,2 km/h.
- Không cần giảm dưới MIN trước khi kéo lên lại; giữ MAX và hoàn tất frame cuối rồi lưu.
- Sau khi đủ frame cuối, hỏi lưu RUN: nút LƯU hoặc BIT3 OK mới lưu; KHÔNG LƯU/đóng bảng bỏ RUN tạm.
- BIT3 chỉ nhận cạnh OFF → ON sau khi bảng mở. Giữ nguyên JSON/RUN.

Trong SETTINGS, bấm ↻ cạnh nút cập nhật để kiểm tra ngay, rồi chọn CẬP NHẬT và xem chi tiết trước khi xác nhận. Ứng dụng cũng kiểm tra một lần khi mở.

[Tải bộ cập nhật v131](releases/v131/Dynotest_Update.exe) · [SHA-256](releases/v131/SHA256.txt) · [Kiểm tra giữ JSON/RUN và khởi động lại](releases/v131/update-checks.txt).

Gói phát hành đã qua quét Microsoft Defender trên Windows với bộ nhận diện được ghi lại trong kiểm tra phát hành. Kết quả quét không phải bảo đảm tuyệt đối về an toàn.

Bản v123 cũ đã rút khỏi kênh cập nhật. Đây là bản dựng lại từ v122; source luôn giữ riêng tư.
