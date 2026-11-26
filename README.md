# kr2-bootstrap-shop

## Контрольная работа №2

Тема: «CSS-фреймворки: разработка интерфейса на Bootstrap или альтернативном CSS-фреймворке».

## Описание проекта

Учебный интернет-магазин «Bootstrap Shop»: многостраничный сайт с каталогом товаров, страницей товара, формой заявки и контактной информацией. Интерфейс реализован на Bootstrap 5.3.3.

## Используемый фреймворк

Bootstrap 5.3.3.

## Способ подключения Bootstrap

Bootstrap подключён локально. Файлы фреймворка размещены в папке `vendor/bootstrap/`.

Используются:

- `vendor/bootstrap/css/bootstrap.min.css`
- `vendor/bootstrap/js/bootstrap.bundle.min.js`

Собственный файл `css/custom.css` подключён после Bootstrap.

## Структура проекта

    kr2-bootstrap-shop/
    ├── index.html
    ├── catalog.html
    ├── product.html
    ├── order.html
    ├── contacts.html
    ├── css/
    │   └── custom.css
    ├── images/
    ├── vendor/
    │   └── bootstrap/
    │       ├── css/
    │       │   └── bootstrap.min.css
    │       └── js/
    │           └── bootstrap.bundle.min.js
    ├── README.md
    └── .gitignore

## Страницы

- `index.html` — главная: navbar, hero-блок, преимущества, популярные товары.
- `catalog.html` — каталог: карточки товаров, badge, alert, модальное окно.
- `product.html` — страница товара: карточка, breadcrumb, accordion, модальное окно.
- `order.html` — форма заявки на Bootstrap-компонентах.
- `contacts.html` — контакты, компонент tabs.

## Реализованные компоненты Bootstrap

- `navbar` (с dropdown);
- `card`;
- `btn` и `btn-outline-*`;
- `badge`;
- `alert`;
- `modal`;
- `form-control`;
- `form-select`;
- `form-check`;
- `input-group`;
- `breadcrumb`;
- `accordion`;
- `tabs`;
- сетка `container` / `row` / `col-*` / `g-*`.

## Опубликованная версия (GitHub Pages)

Ссылка на сайт: https://cruddykot.github.io/kr2-bootstrap-shop/

## Самостоятельные доработки

- Локальное подключение Bootstrap без CDN (папка `vendor/bootstrap/`).
- Добавлена страница `contacts.html` с компонентом `tabs`.
- На странице товара используется `accordion` для характеристик и условий доставки.
- Адаптивная навигация с выпадающим меню `dropdown` на всех страницах.
- Публикация проекта через GitHub Pages.

## Автор

- ФИО: Назаров Илья
- Группа: ЭФБО-13-25
- Дисциплина: Фронтенд и бэкенд разработка
- Семестр: 3, 2026/2027