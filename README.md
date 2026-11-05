# Сайт игры «РУБЕЖ: Сектор 9» (BULWARK: Sector 9)

Статический сайт для карточек RuStore и Microsoft Store: лендинг на русском и английском,
политика конфиденциальности на двух языках.

**Адрес:** https://yurinkonstantin.github.io/onetapdefense-site/

## Страницы

| Файл | Адрес | Назначение |
|---|---|---|
| `index.html` | `/` | Лендинг, русский |
| `en.html` | `/en.html` | Лендинг, английский |
| `privacy.html` | `/privacy.html` | Политика конфиденциальности, русский (для RuStore) |
| `privacy-en.html` | `/privacy-en.html` | Privacy Policy, английский (для Microsoft Store) |
| `404.html` | — | Страница ошибки |

## Ссылки для карточек магазинов

- RuStore, «Ссылка на политику конфиденциальности»:
  `https://yurinkonstantin.github.io/onetapdefense-site/privacy.html`
- Microsoft Store, Privacy policy URL:
  `https://yurinkonstantin.github.io/onetapdefense-site/privacy-en.html`
- Сайт поддержки (Support URL / Website):
  `https://yurinkonstantin.github.io/onetapdefense-site/`

## Технически

- Чистый HTML + CSS, без сборки, без JavaScript, без внешних CDN — сайт работает офлайн и без cookies.
- Хостинг: GitHub Pages, ветка `main`, каталог `/` (в корне репозитория).
- Графика в `assets/img/` собрана скриптом `tools/site_assets.py` из материалов `store/` игры.

## Обновление

1. Правки — в `index.html`, `en.html`, `privacy.html`, `privacy-en.html`, `assets/css/style.css`.
2. При изменении политики конфиденциальности обновить дату вступления в силу и `lastmod` в `sitemap.xml`.
3. Коммит и пуш в `main`; GitHub Pages пересобирается автоматически за 1–2 минуты.

## Лицензия

Тексты и оформление сайта — © 2026, разработчик игры «РУБЕЖ: Сектор 9».
Скриншоты и иконка — материалы той же игры.
