# Màn Sale TTTT - Thu thập thông tin Merchant

Giao diện tĩnh, không cần build. Mở `index.html` bằng trình duyệt (hoặc chạy `npx serve .`).

## Cấu trúc
- `index.html`: màn hình (template + logic)
- `support.js`: runtime của Design Component, bắt buộc đi kèm
- `nnkd-data.js`: danh sách NNKD cấp 4 và giấy phép con (`window.NNKD`)

## GitHub Pages
Settings → Pages → Deploy from branch → `main` / root.

## Lưu ý
- Font Inter và JetBrains Mono tải từ Google Fonts.
- Dữ liệu hiện là mock trong state của component; chưa gọi API.
