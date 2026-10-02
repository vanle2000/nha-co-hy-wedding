# Nhà Có Hỷ — Wedding Planner for Phát & Thảo 💍

Trang kế hoạch đám cưới truyền thống Việt Nam tại Huế, chủ đề **"Về Chung Một Nhà" — Hoàng Kim Huế × Regency Bridgerton**,
thiết kế riêng cho Phát & Thảo: bạn học cấp ba, yêu nhau 6 năm, 3 năm yêu xa Đà Nẵng – Huế, và nay *về chung một nhà*
vào **Thứ Hai 15/02/2027 (mùng 10 tháng Giêng, năm Đinh Mùi)** — tiệc trưa tại GOLDLAND PLAZA, Huế, 700–800 khách.

## Cách mở trang
🌐 **Trang web đang chạy tại: https://vanle2000.github.io/nha-co-hy-wedding/**

Hoặc **nhấp đúp vào `index.html`** để mở trong trình duyệt. Không cần cài đặt gì cả.

Hoặc chạy một server tĩnh (tùy chọn):
```bash
cd wedding-hue
python3 -m http.server 8000
# rồi mở http://localhost:8000
```

## Trang gồm những phần nào
1. **Trang chủ + đồng hồ đếm ngược** đến ngày cưới (15/02/2027, 9:00 sáng)
2. **Chuyện tình** — hành trình 6 năm, 3 năm yêu xa
3. **Chuẩn bị 4 tháng rưỡi** — việc cần làm theo từng mốc, tính ngược từ ngày cưới
4. **Nghi lễ truyền thống** — Lễ dạm ngõ · Lễ ăn hỏi · Lễ cưới (giải thích chi tiết)
5. **Địa điểm** — GOLDLAND PLAZA (14–16–18–20 Lý Thường Kiệt, Thuận Hóa, Huế), 700–800 khách
6. **Sơ đồ sảnh tiệc** — bố trí ~70–80 bàn, khu lễ tân, check-in, gallery
7. **Trang trí & chủ đề không gian** — decor "Về Chung Một Nhà"
8. **Lịch trình ngày cưới** — từng mốc giờ, nghi lễ sáng + tiệc trưa
9. **Checklist tương tác** — tích hoàn thành, tự lưu trên trình duyệt
10. **Ngân sách tham khảo** (VND) — đã quy mô theo 700–800 khách
11. **Chủ đề & phong cách** — "Về Chung Một Nhà · Hoàng Kim Huế" (vàng hoàng kim – trắng ngà – champagne, hợp mệnh Kim)
12. **Ý tưởng chạm đến trái tim** — những chi tiết ấm áp
13. **Thời tiết** — khí hậu trung bình giữa tháng 2 ở Huế + link dự báo
14. **Thông tin cưới tại Huế** — bối cảnh chụp hình, đón khách


## Phong cách Bridgerton
Hai triều đình cùng một thập niên — London Regency (1813–1815) & Kinh thành Huế thời Gia Long (1802–1820). Trang web dùng
font Cormorant Garamond + Great Vibes, khung filigree mạ vàng, thư ngỏ giọng *"Kính gửi Quý Độc Giả thân mến"*, niêm sáp đỏ son "P❦T";
decor gợi ý: đèn chùm pha lê, tứ tấu đàn dây, cổng hoa tử đằng, tháp macaron, thiệp thư tay niêm sáp.

## Cần tùy chỉnh
Mở `index.html` bằng trình soạn thảo và sửa khi cần:
- **Tên:** đã đặt sẵn **Phát & Thảo** (chú rể & cô dâu).
- **Ngày cưới:** đã đặt `const WEDDING_DATE = new Date('2027-02-15T09:00:00');`
  (gần cuối file) — đồng hồ đếm ngược chạy đúng 9:00 sáng Thứ Hai 15/02/2027.
- **Ngân sách & khách mời:** điền số liệu thật của gia đình.

## Lưu ý văn hóa
Số mâm quả, lễ vật và nghi thức **khác nhau tùy gia đình, vùng miền và dòng họ**.
Phần nội dung là khung tham khảo theo phong tục phổ biến ở Huế / miền Trung —
**hãy luôn hỏi và thống nhất với người lớn / trưởng họ hai bên trước.**

---

*English:* A ready-to-open (double-click `index.html`) Vietnamese wedding-planning site
tailored to a Huế wedding and the couple's long-distance love story. Edit the names, the
`WEDDING_DATE` line, and the budget/guest numbers to make it yours. Treat the ceremony
details as a well-researched reference and always confirm specifics with both families' elders.
