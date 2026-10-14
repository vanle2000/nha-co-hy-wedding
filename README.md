# Nhà Có Hỷ — Wedding Planner for Phát & Thảo 💍

Trang kế hoạch đám cưới truyền thống Việt Nam tại Huế, chủ đề **"Về Chung Một Nhà" — Hoàng Kim Huế × Regency Bridgerton**,
thiết kế riêng cho Phát & Thảo: bạn học từ thời cấp ba, bên nhau 6 năm và nay *về chung một nhà*
vào **Chủ Nhật 14/02/2027 (mùng 9 tháng Giêng, năm Đinh Mùi)** — tiệc trưa tại GOLDLAND PLAZA, Huế, 700–800 khách.

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
1. Trang chủ &amp; đồng hồ đếm ngược
2. Chuyện của Phát &amp; Thảo
3. 8 việc chính cần hoàn thành
4. Nghi lễ ngày cưới
5. Địa điểm GOLDLAND PLAZA
6. Lịch trình ngày cưới
7. Checklist chuẩn bị rút gọn
8. Spreadsheet ngân sách
9. Ý tưởng đã chọn &amp; mô hình Đèn Hỷ 3D
10. Thời tiết tham khảo

## Phong cách Bridgerton
Hai triều đình cùng một thập niên — London Regency (1813–1815) & Kinh thành Huế thời Gia Long (1802–1820). Trang web dùng
font Cormorant Garamond + Great Vibes, khung filigree mạ vàng, thư ngỏ giọng *"Kính gửi Quý Độc Giả thân mến"*, niêm sáp đỏ son "P❦T";
decor gợi ý: đèn chùm pha lê, tứ tấu đàn dây, cổng hoa tử đằng, tháp macaron, thiệp thư tay niêm sáp.

## Cần tùy chỉnh
Mở `index.html` bằng trình soạn thảo và sửa khi cần:
- **Tên:** đã đặt sẵn **Phát & Thảo** (chú rể & cô dâu).
- **Ngày cưới:** đã đặt `const WEDDING_DATE = new Date('2027-02-14T09:00:00');`
  (gần cuối file) — đồng hồ đếm ngược chạy đúng 9:00 sáng Chủ Nhật 14/02/2027.
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
