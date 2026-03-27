# SUNWARD — Лендинг официального дилера

Промо-сайт компании **SUNWARD** — международного производителя тяжёлой строительной техники. Страница представляет российского дилера **ТВС Агротехника** и включает каталог продукции, преимущества бренда, услуги и контактную информацию.

**Live:** [vkrasnovid.github.io/sunward-landing](https://vkrasnovid.github.io/sunward-landing/)
**Оригинал:** [sunward-tvsagrotechnika.ru](https://sunward-tvsagrotechnika.ru/)

![Screenshot](https://via.placeholder.com/1200x630?text=SUNWARD+Landing+Page)

## Tech Stack

- HTML5 (семантическая разметка, Open Graph)
- CSS3 (кастомные свойства, flexbox/grid, анимации)
- Vanilla JavaScript (без фреймворков и зависимостей)
- Google Fonts (Inter, Space Grotesk)
- SVG-иконки (спрайт `assets/icons.svg`)

## Features

- Адаптивный дизайн (мобильные, планшеты, десктоп)
- Мобильное меню-бургер
- Плавная прокрутка к секциям
- Каталог техники: экскаваторы, погрузчики, подъёмники, спецтехника
- Блок преимуществ с анимированной статистикой
- Секции «О компании», «Услуги», «Контакты»
- SEO-оптимизация (мета-теги, Open Graph)
- Деплой на GitHub Pages

## Project Structure

```
├── index.html          # Основная страница
├── css/style.css       # Стили
├── js/main.js          # Скрипты
└── assets/             # Иконки и ресурсы
    ├── favicon.svg
    └── icons.svg
```

## How to Run

Фреймворки и сборщики не требуются — достаточно открыть `index.html` в браузере:

```bash
# Вариант 1: просто открыть файл
open index.html        # macOS
xdg-open index.html    # Linux

# Вариант 2: локальный сервер
python3 -m http.server 8000
# → http://localhost:8000
```

## License

MIT
