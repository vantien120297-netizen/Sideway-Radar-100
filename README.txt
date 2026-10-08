SIDEWAY RADAR iPHONE V2
========================

Mục tiêu:
- Chạy trực tiếp trên iPhone, KHÔNG phụ thuộc Windows.
- Lấy dữ liệu trực tiếp từ Binance Public API.
- Top 100 Binance Spot USDT.
- 1H / 4H / 1D.
- SIDEWAY / PRE-BREAKOUT / BREAKOUT / RADAR.
- Tự tách:
  1) CƠ HỘI SIDEWAY: SIDEWAY >=75, PRE >=75, BREAKOUT <80
  2) TOP RADAR
  3) ĐÃ BREAKOUT: BREAKOUT >=80
- Không biểu đồ nến.
- Không Telegram, không giao dịch.

CÁCH TRIỂN KHAI:
1. Đưa 4 file lên GitHub Pages, Cloudflare Pages hoặc một web hosting HTTPS.
2. Mở đường dẫn HTTPS trên iPhone Safari.
3. Chọn Chia sẻ -> Thêm vào Màn hình chính.
4. Từ đó iPhone mở SIDEWAY RADAR như một web app độc lập.
5. Windows có thể tắt hoàn toàn.

LƯU Ý:
- iPhone vẫn cần Internet để lấy dữ liệu Binance.
- Đây là bản PWA chạy client-side; không cần Python/Flask/server Windows.
- Khi triển khai thật, nên dùng HTTPS.
