# Thượng Đỉnh Yến Hoa — Website v8

## Deploy nhanh
- **Cloudflare Pages / Netlify / Vercel**: drag drop cả thư mục hoặc kết nối GitHub repo → entry point tự động `index.html`
- **GitHub Pages**: đẩy code lên nhánh `main`, vào Settings → Pages → Deploy from branch `main` / root

## Cấu trúc
- `index.html` — trang chủ (bản deploy chính, copy của `index-v8.html`)
- `index-v8.html`, `ve-chung-toi-v8.html`, `san-pham-yen-chung-san-v8.html`, `cong-dong-v8.html`, `tai-tro-v8.html` — 5 trang
- `css/` — style-v8, carousel-v8, about, product
- `js/` — main-v7, carousel-v7, product
- `assets/` — fonts, images (webp + jpg), motifs, product-photos

## Local preview
```bash
python -m http.server 8571
# http://localhost:8571
```

## Cập nhật
Kéo file HTML/CSS mới ghi đè, commit push. Không có build step.
