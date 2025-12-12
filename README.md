# Metrotime — сайт-визитка (статический)

Это шаблон одностраничного лендинга + страницы `privacy.html` и `support.html`.
Подходит для:
- GitHub Pages / Cloudflare Pages / Netlify / Vercel
- ссылки "Marketing URL" и "Support URL" в App Store Connect

## Быстрый старт

1) Откройте `index.html` и замените плейсхолдеры:
- `APP_STORE_LINK` → ссылка на App Store
- `SUPPORT_EMAIL` → почта поддержки
- `TELEGRAM_LINK` → ссылка на Telegram

2) Добавьте скриншоты:
- положите PNG/JPG в `assets/screens/` и назовите `01.png`, `02.png`, `03.png` (или измените пути в HTML)

3) Заливка на GitHub Pages:
- создайте репозиторий, загрузите содержимое папки
- Settings → Pages → Deploy from a branch → `main` / `/root`

## Настройка домена (опционально)
- добавьте файл `CNAME` в корень и укажите домен, затем подключите DNS.

## Рекомендации
- Добавьте реальный `og:image` (1200×630) в `assets/og.png`
- Обновите тексты под текущий функционал приложения
