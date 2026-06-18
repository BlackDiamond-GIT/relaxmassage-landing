# Relax masáž — landing

Статичний односторінковий лендінг для [relaxmassageprague.cz](https://relaxmassageprague.cz).

## Файли

- `index.html` — сторінка (CS / EN / RU, CTA WhatsApp напряму на wa.me)
- `render.yaml` — Render Blueprint (Static Site)

## Деплой

Push у `main` → автоматичний деплой на Render (сервіс `relax-massage-landing`).

## Оновлення

1. Змінити `index.html`
2. `git commit` + `git push origin main`

## Аналітика кліків

Клік на CTA відкриває WhatsApp напряму. Паралельно відправляється beacon на бекенд tantra-club (`CLICK_TRACK_URL` у `index.html`).

Статистика: `/admin/` на tantra-club → **Relax landing clicks**.
