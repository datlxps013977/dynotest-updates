# DynoTest DATNL — Updates

Kênh cập nhật công khai chính thức. Source code giữ trong repo riêng tư.

## Bản hiện tại: ver1.1.70

Menu CHART mở ngay kể cả offline, chưa có status hoặc BIT4 OFF; bấm lại khôi phục/đưa cửa sổ hiện có lên trước. Active chỉ theo cửa sổ mở/đóng. Nếu chart đã mở trước khi kết nối, gửi BIT4 ON sau status hợp lệ đầu tiên, OR bit để giữ các trạng thái khác và không gửi lặp mỗi frame. Khi phần cứng xác nhận ON, BIT ON/OFF vẫn mở/đóng chart; nút X gửi OFF như trước. Không đổi điều kiện đo, RAW hay tính toán. Giữ sửa lưới AFR v169.

Bản phát hành đã qua kiểm tra Windows, quét Defender cho ứng dụng và bộ cập nhật, kiểm tra giữ JSON/RUN và khởi động lại.

Trong SETTINGS, bấm ↻ để kiểm tra rồi chọn CẬP NHẬT.

[Tải bộ cập nhật v170](releases/v170/Dynotest_Update.exe) · [SHA-256](releases/v170/SHA256.txt) · [Kiểm tra giữ dữ liệu](releases/v170/update-checks.txt).
