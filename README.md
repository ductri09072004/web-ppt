# Web PPT — Configurable KPI Performance Management Platform

Bài thuyết trình dạng web một trang: các slide xếp chồng, cuộn hoặc dùng phím để chuyển, có hiệu ứng xuất hiện cho từng phần.

## Chạy

Mở trực tiếp `index.html`, hoặc chạy máy chủ cục bộ:

```bash
python -m http.server 5178
```

Sau đó vào http://localhost:5178.

## Phím tắt

| Phím | Tác dụng |
|---|---|
| ↓ → PageDown Space | Slide kế tiếp |
| ↑ ← PageUp | Slide trước |
| P | Phát hoặc dừng video ở slide đang xem |
| R | Ở slide 2: hiển thị các cách chấm KPI |
| A | Nhảy tới phụ lục |
| F | Toàn màn hình |

## Cấu trúc

- `index.html`: toàn bộ slide, CSS và JavaScript (không dùng thư viện ngoài).
- `assets/video1.mp4`: Video 1 — Câu chuyện sản phẩm.
- `assets/video2_demo.mp4`: Video 2 — Demo (chưa có; đặt file này vào thì slide 7 tự hiện video).
