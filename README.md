# AHA Studio

Bộ công cụ AI cục bộ cho người sáng tạo, kết nối Photoshop, Premiere Pro và các
nhà cung cấp AI trong một quy trình làm việc thống nhất. Ảnh và video được xử lý
trên máy của bạn bằng phiên đăng nhập hoặc nhà cung cấp do bạn chọn; byte ảnh và
video không được chuyển tiếp qua máy chủ AHA Studio.

> **Bản hiện tại:** AHA Studio **2.26.0** (Technical Preview) — phát hành ngày
> **15/10/2026** cho Windows 10/11 64-bit và macOS Apple Silicon.

## Tải về và cài đặt

Hướng dẫn chính thức bao gồm tải file, cài đặt, đăng nhập và thiết lập các plugin:

**→ [ahastudio.xyz/download](https://ahastudio.xyz/download)**

Bạn cũng có thể xem [release 2.26.0 trên GitHub](https://github.com/AIhugART/AHA-studio/releases/tag/v2.26.0).

| Nền tảng | Bộ cài | SHA-256 |
|---|---|---|
| **Windows 10/11** (64-bit) | [`AHA-Studio-Setup-2.26.0.exe`](https://github.com/AIhugART/AHA-studio/releases/download/v2.26.0/AHA-Studio-Setup-2.26.0.exe) | `33a4b5f21cca3cac36431b5a2693dfc27fb55125e4f8cadf1bd031be19a656fc` |
| **macOS** Apple Silicon (M-series) | [`AHA-Studio-macos-arm64-2.26.0.dmg`](https://github.com/AIhugART/AHA-studio/releases/download/v2.26.0/AHA-Studio-macos-arm64-2.26.0.dmg) | `2537cbf63e34a373a9a038a9dc21b5be5d8ed9f6f1fadc3803e42c20a904c14b` |

macOS Intel hiện chưa được hỗ trợ. Nếu bạn không chắc nên tải file nào hoặc gặp
cảnh báo bảo mật của hệ điều hành, hãy dùng hướng dẫn cài đặt ở trên.

## Có gì mới trong 2.26.0

- **AHA Clip cho Premiere Pro** được AHA Studio tự cài đặt và tự cập nhật, không
  còn bước cài thủ công qua Creative Cloud.
- AHA Clip 0.2.0 hỗ trợ chọn khung hình bắt đầu/kết thúc cho từng vị trí tham chiếu.
- Bổ sung xoá logo trên video tạo bởi Flow.
- Làm mới thông tin bản cập nhật trước khi áp dụng để tránh dùng manifest cũ.
- Mở rộng vùng ảnh tối đa 200% và sửa các thao tác trong menu **Send to**.

## Các thành phần

- **AHA Studio** — ứng dụng trung tâm chạy cục bộ.
- **AHA Paint** — panel AI cho Adobe Photoshop.
- **AHA Clip** — panel AI cho Adobe Premiere Pro.
- **AHA Studio Bridge** — tiện ích trình duyệt kết nối các nhà cung cấp AI được hỗ trợ.

## Repo này chứa gì

Repo public này chỉ chứa tài liệu và các bản phát hành. File cài đặt nằm trong
tab [Releases](https://github.com/AIhugART/AHA-studio/releases), không nằm trong
danh sách file của nhánh `main`.

**Mã nguồn không được công khai trong repo này.**
