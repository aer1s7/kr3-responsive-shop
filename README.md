# Контрольная работа №3

Тема: «Адаптивная вёрстка и доступность многостраничного HTML/CSS-сайта».

## Описание

Проект представляет собой адаптивную версию многостраничного HTML/CSS-сайта интернет-магазина.

## Практическая работа №12

Выполнено:

- создан отдельный репозиторий `kr3-responsive-shop`;
- перенесена основа проекта КР №1;
- добавлен файл `css/responsive.css`;
- применён подход Mobile First;
- добавлены медиазапросы;
- адаптирована навигация;
- адаптирован hero-блок;
- адаптирована сетка карточек;
- адаптирован каталог;
- добавлены responsive images;
- адаптирована форма заявки;
- адаптирована таблица характеристик;
- выполнена проверка через DevTools.

## Проверенные ширины

- 360px;
- 430px;
- 768px;
- 1024px;
- 1440px.

## Практическая работа №13

Тема: «A11y-аудит и обеспечение доступности. Использование Lighthouse и анализ проблем доступности».

Выполнено:

- проверена семантическая структура страниц;
- добавлена ссылка пропуска к основному содержимому;
- проверена навигация с клавиатуры;
- добавлен или исправлен видимый фокус;
- проверены изображения и alt-описания;
- проверены формы и связанные label;
- проверены кнопки и ссылки;
- исправлена контрастность отдельных элементов;
- проверено модальное окно;
- выполнен Lighthouse-аудит;
- сохранён Lighthouse-отчёт или скриншот;
- исправлены найденные проблемы доступности.

## Lighthouse

### Link: https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Faer1s7.github.io%2Fkr3-responsive-shop%2F&strategy=mobile&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa&utm_source=lh-chrome-ext

Проверены страницы:

- `index.html`;
- `catalog.html`;
- `product.html`.
- `contacts.html`.
- `order.html`.

Отчёт сохранён в папке `lighthouse/`.


## Структура проекта

kr3-responsive-shop/
├── index.html
├── catalog.html
├── product.html
├── order.html
├── contacts.html
├── css/
│   ├── style.css
│   └── responsive.css
├── js/
│   └── main.js
├── images/
├── README.md
└── .gitignore
