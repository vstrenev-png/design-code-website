# Design-Code — Уебсайт

Статичен уебсайт на студио Design-Code (интериорен дизайн). Чист HTML/CSS/JS — без build процес.

## Структура

- `index.html` — начална страница (hero, услуги, проекти, видео, за нас, контакти)
- `contact.html` — форма за запитване + бутон за платена консултация (200 €)
- `project-*.html` — 5 страници за проекти (Витоша, Градина, Мерак, Тишина, Ритуал)
- `project.css` / `project.js` — стилове и логика на проектните страници
- `assets/` — лого, favicon, изображения, видео (showreel.mp4), lenis.min.js

## Настройка преди публикуване

В `contact.html` попълнете:

- `STRIPE_PAYMENT_LINK` — линк от Stripe → Payment Links (продукт 200 €)
- `FORM_ENDPOINT` — endpoint от Formspree/Web3Forms за формата

## Публикуване

1. **Класически хостинг (cPanel):** качете цялото съдържание в `public_html`.
2. **GitHub Pages:** Settings → Pages → Deploy from branch → `main` / `(root)`.
3. **Netlify / Vercel / Cloudflare Pages:** свържете хранилището, без build команда.
