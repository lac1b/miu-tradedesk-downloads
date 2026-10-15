# Miu TradeDesk — bản tải thử nghiệm

Kho này chỉ phát hành bộ cài Windows, EA MT5 và checksum để kiểm tra tính toàn vẹn. Mã backend và dữ liệu khách hàng không nằm trong kho này.

[Tải bộ cài, EA và checksum v0.1.2](https://github.com/lac1b/miu-tradedesk-downloads/releases/tag/v0.1.2) · [Đăng ký tài khoản](https://trade-desk-c2c68.web.app/)

## Phiên bản

- Ứng dụng Windows x64: **0.1.2**.
- EA thương mại: **9.36**.
- Phạm vi: **bản thử nghiệm theo lời mời, chỉ tài khoản MT5 demo**. Không dùng để giao dịch tiền thật.

Tải các tệp tại mục **Releases**:

- `Miu-TradeDesk-Setup-0.1.2.exe` — bộ cài Windows.
- `Miu_TradeDesk_Commercial.ex5` — EA dùng trong MT5.
- `Miu-TradeDesk-Setup-0.1.2.sha256.txt` — checksum bộ cài.
- `SHA256SUMS.txt` — checksum EA.

## Bắt đầu

1. Đăng ký bằng email đã được mời tại [website TradeDesk](https://trade-desk-c2c68.web.app/).
2. Nhận ID, key bản quyền và mật khẩu khởi tạo qua email; đăng nhập ứng dụng và đổi mật khẩu ở lần đầu.
3. Trong ứng dụng, mở **Gói & Thanh toán** để xem trạng thái gói. Tính năng thanh toán chỉ khả dụng khi chủ sản phẩm đã kích hoạt cổng thanh toán.
4. Với gói còn hiệu lực, mở **Liên kết MT5**, tạo mã và nhập vào `InpPairingCode` của EA trên MT5 demo.

Không cung cấp mật khẩu giao dịch MT5, Firebase Secret hay khóa quản trị cho ứng dụng hoặc nhân viên hỗ trợ.

## Tính toàn vẹn và cập nhật

SHA-256 của bộ cài:

`CC05BDE5728AF53010C035659A0663BB8F3C53CE37055C532BF33582934BF3B1`

SHA-256 của EA:

`AD9A0B46297492F7345A9C648A1B36B41CABAB8E90981E3948D0FBE3AF100EB9`

Bộ cài hiện **chưa ký số** và **chưa có cập nhật tự động**. Chỉ cài sau khi xác minh đúng nguồn tải và checksum; không tắt các tính năng bảo vệ của Windows. Nếu đang dùng phiên bản cũ, đóng ứng dụng trước khi cập nhật thủ công.

Bản thử sử dụng hạ tầng miễn phí; thời gian khởi động máy chủ và độ trễ có thể thay đổi. Trạng thái đã liên kết chưa khẳng định EA đã gửi được dữ liệu; cần kiểm tra kết nối trên MT5 demo.
