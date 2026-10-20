# Hướng Dẫn Nạp Skill UGC KKHome AI Vào Muse

© 2026 · KKHome AI - JennyKieu

Skill này giúp Muse, từ một ảnh mẫu sản phẩm, tự vận hành 3 chặng: **tạo 5 phương án ảnh → viết kịch bản UGC liền mạch 2 phân cảnh → tạo poster thu hút click** cho TikTok Shop / Shopee.

## Gói skill gồm

- `SKILL.md` — chỉ thị vận hành (bộ não của skill).
- `skill.yaml` — thông tin nhận diện skill.
- `references/bo-lenh-ngan.md` — bộ lệnh ngắn KKHomeAI (từ điển lệnh + ví dụ), skill tự đọc khi làm việc.

## Cách 1 — Nạp từ xa bằng liên kết (nhanh nhất)

Kho skill chính thức trên GitHub: https://github.com/JennyKieu1102/SkillUGCWithMuse
(Tải nhanh cả gói: nút **Code → Download ZIP** trong repo, hoặc https://github.com/JennyKieu1102/SkillUGCWithMuse/archive/refs/heads/main.zip)

1. Tải gói skill từ GitHub (link trên) hoặc nhận liên kết từ KKHome AI.
2. Mở một chat Muse mới và gửi đúng câu này, kèm các file trong gói:

> **"Nạp Skill UGC này và cùng làm việc bạn nhé!"**

3. Muse sẽ đọc gói skill. Từ đó bạn chỉ cần đưa ảnh sản phẩm và gõ lệnh ngắn (xem bảng dưới).

## Cách 2 — Lưu skill cố định trong Muse của bạn

Giải nén gói skill và đặt thư mục `kkhomeai_ugc_media` vào thư mục skill tùy chỉnh của Muse (`~/workspace/custom-skills/`). Skill sẽ luôn sẵn sàng trong mọi cuộc trò chuyện, không cần nạp lại.

## Bảng lệnh ngắn sau khi nạp skill

| Bạn gõ | Muse sẽ làm |
|---|---|
| "Tạo ảnh cho sản phẩm này" (+ ảnh sản phẩm) | Đề xuất 5 phương án ảnh và tạo ảnh theo lựa chọn của bạn. |
| "Tạo kịch bản cho sản phẩm này" | Viết kịch bản UGC liền mạch 2 phân cảnh × 10 giây, thoại tiếng Việt giọng nữ miền Nam, có CTA giỏ hàng. |
| "Tạo poster cho sản phẩm này" | Tạo poster thu hút click, tiêu đề 5–7 chữ. |
| "Làm trọn gói sản phẩm này" | Chạy cả 3 chặng một mạch: ảnh → kịch bản → poster. |

Mẹo: kèm theo ảnh sản phẩm, hãy nói thêm sản phẩm dùng để làm gì, điểm mạnh nhất và ưu đãi đang có — hook và CTA sẽ trúng ý hơn hẳn.
