# Aturan Pembuatan Artikel Blog Merchandise Kantor

Setiap artikel blog baru di proyek ini **HARUS** mematuhi panduan di [`AGENTS.md`](file:///d:/TUGAS%20KULIAH/Project%20MKI/MerchandiseKantor/vendormerchandise/AGENTS.md).

## Ringkasan Aturan Kunci:
1. **Dilarang** membuat HTML artikel dengan template standalone / CSS inline baru.
2. **Wajib** menyertakan file CSS bawaan proyek:
   - `assets/vendor/bootstrap/css/bootstrap.min.css`
   - `assets/vendor/bootstrap-icons/bootstrap-icons.css`
   - `assets/vendor/aos/aos.css`
   - `assets/css/main.css?v=2`
3. **Wajib** mengikuti struktur komponen baku:
   - Body class: `blog-details-page`
   - Header: `<header id="header" class="header d-flex align-items-center fixed-top">` (Logo White & Blue)
   - Navmenu: `<nav id="navmenu" class="navmenu">`
   - Main: `<main class="main">`
   - Component: `breadcrumb-bar`, `article-layout`, `article-main`, `article-title`, `article-top-meta` (Erlang Sinatrya), `featured-image-wrap`, `summary-box`, `toc-box` (Auto TOC), `article-body`, `baca-juga-box`, `body-figure`, `promo-banner`, `article-faq` (Mini Accordion), `share-article-box`, `article-tags-footer`.
   - Sidebar: `article-sidebar`, `sidebar-author-card` (Erlang Sinatrya), `sidebar-related` (3 Artikel Terkait).
   - Rekomendasi Produk: `related-articles-section`.
   - CTA Section: `cta-section py-5 light-background`.
   - Footer: `footer position-relative dark-background`.
   - Floating WA: `whatsapp-float`.
   - Scripts: Bootstrap bundle, AOS, main.js, dan inline script Auto TOC & FAQ.
