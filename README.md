# Оселя — сайт для деплою

Статичний сайт: завантажте вміст папки на будь-який хостинг (Netlify, Vercel, Cloudflare Pages, GitHub Pages).
Головний файл — `index.html`.

## Файли
- `index.html` — сайт
- `favicon.svg`, `apple-touch-icon.png`, `og-image.jpg` — ТИМЧАСОВІ, замініть на свої (ті самі назви)
- `robots.txt`, `sitemap.xml` — для пошуковиків

## Перед запуском
1. У `index.html`, `robots.txt`, `sitemap.xml` замінити `https://TODO-your-domain.com` на реальний домен.
2. Підключити відправку двох форм (шукайте `TODO` в `index.html`).
3. Замінити демонстраційні контакти, соцмережі, відгуки, фото з Unsplash.
4. Вставити GA4 / Meta Pixel (коментарі в `<head>`).
5. Після деплою перевірити pagespeed.web.dev та opengraph.xyz.
