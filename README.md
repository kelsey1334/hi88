# Hi88 Landing (GitHub Pages)

Landing page SEO-ready cho từ khóa **Hi88** — *nhà cái cá cược trực tuyến uy tín*. Triển khai nhanh trên GitHub Pages.

## Hướng dẫn triển khai
1. Tạo repo mới công khai, đặt tên tùy thích (ví dụ `hi88`).
2. Tải file ZIP này lên và giải nén ở root (cùng cấp với `index.html`).
3. Vào **Settings → Pages**, chọn Source là `Deploy from a branch` và Branch `main` với folder `/ (root)`.
4. Sau khi publish, cập nhật các URL trong `index.html`, `robots.txt`, `sitemap.xml` từ `your-username` → username thật.
5. (Tuỳ chọn) Cấu hình form:
   - Tìm thuộc tính `action="https://formspree.io/f/your-id"` và đổi sang endpoint form thật của bạn (Formspree, Netlify Forms, …).

## Cấu trúc
- `index.html` — Landing page chính (semantic HTML + structured data).
- `robots.txt` — Cho phép index, trỏ sitemap.
- `sitemap.xml` — Mẫu sitemap tối thiểu.
- `404.html` — Trang 404.
- `logo.png`, `og-image.jpg` — Ảnh chia sẻ MXH/OG & logo.

## Gợi ý SEO
- Điền đầy đủ thông tin liên hệ thật.
- Đảm bảo canonical, OG URL trỏ đúng domain thật.
- Theo dõi Core Web Vitals trong Search Console/Pagespeed.
