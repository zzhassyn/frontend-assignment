# Assignment #1: HTML & CSS Basics &bull; Frontend Web Engineering

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-brightgreen?logo=github)](https://zzhassyn.github.io/frontend-assignment/)
[![Astana IT University](https://img.shields.io/badge/Astana%20IT%20University-SE--24-blue)](https://astanait.edu.kz)
[![HTML5 & CSS3](https://img.shields.io/badge/Standard-HTML5%20%7C%20CSS3-orange)](#)

---

## 👥 Group Project Team (3 Participants)

| # | Full Name | Role in Assignment | Contact / GitHub |
|---|-----------|--------------------|------------------|
| 1 | **Zhassyn Zhalynuly** | Group Lead &bull; Frontend Development &bull; Task 1 &amp; Task 4 | [@zzhassyn](https://github.com/zzhassyn) |
| 2 | **Mardan Khalilov** | UI/UX Design &bull; Wireframes &amp; Layout &bull; Task 2 &amp; Task 5 | [@MardanKhalilov](https://github.com/) |
| 3 | **Raiymbek Maksotov** | Fullstack &bull; Documentation &bull; Task 3 (Tribute) &amp; Specs | [@RaiymbekMaksotov](https://github.com/) |

---

## 🌐 Live Website & Deployment

The complete project is configured for **GitHub Pages** deployment:
- **Live URL:** [https://zzhassyn.github.io/frontend-assignment/](https://zzhassyn.github.io/frontend-assignment/)
- **Repository URL:** [https://github.com/zzhassyn/frontend-assignment](https://github.com/zzhassyn/frontend-assignment)

A shared top navigation bar (`navbar`) connects all 5 tasks across separate pages.

---

## 📁 Repository Structure (Структура проекта)

Все стили вынесены в отдельную папку `css/`, а код упрощен до чистого базового уровня для легкой защиты:

```text
frontend-assignment/
├── index.html                   # Task 1: Личная веб-страница (Personal Webpage)
├── task2.html                   # Task 2: Макет на <div> и float (Zero Flexbox / Zero Grid)
├── task3.html                   # Task 3: Редирект на exercise1/index.html
├── task4.html                   # Task 4: Таблица оценок и форма обратной связи
├── task5.html                   # Task 5: Midterm проект (DevSphere), Sitemap и 5 вайрфреймов
├── css/                         # 📁 Папка со стилями CSS
│   ├── styles.css               # Стили для Task 1 (селекторы элементов, ID, классов, box model)
│   ├── task2.css                # Стили для Task 2 (float: left, float: right, clear: both)
│   ├── task3.css                # Стили для Task 3 (Tribute Page: шрифты, портрет, списки)
│   ├── task4.css                # Стили для Task 4 (таблица: :nth-child, .highlight-row, форма)
│   └── task5.css                # Стили для Task 5 (карточки вайрфреймов и схема sitemap)
├── exercise1/                   # Папка Task 3 по требованию задания (Step 0)
│   ├── index.html               # Task 3: Alan Turing Tribute Page
│   └── styles.css               # Task 3: Стили страницы Тьюринга
├── images/                      # Медиафайлы и схемы вайрфреймов
│   ├── avatar.svg               # Аватар студента
│   ├── alan_turing.svg          # Портрет Алана Тьюринга
│   └── wireframes/              # 5 векторных схем вайрфреймов
│       ├── page1_home.svg       # Page 1: Home / Landing
│       ├── page2_projects.svg   # Page 2: Projects Catalog
│       ├── page3_details.svg    # Page 3: Project Details
│       ├── page4_community.svg  # Page 4: Community Directory
│       └── page5_contact.svg    # Page 5: Contact & Support
├── assignment1_frontend.docx    # Исходный документ с требованиями лабораторной
└── README.md                    # Документация и шпаргалка для защиты
```

---

## 📋 Task Overview & Requirements Fulfillment

### 🔹 Task 1: Introduction to HTML & CSS (`index.html`, `css/styles.css`)
- **HTML:** Семантическая и простая структура (`<header id="main-header">`, `<main>`, `<section>`, `<h1>`, `<h2>`, `<p>`).
- **Списки:**
  - Упорядоченный список (`<ol>` из 5 пунктов): этапы веб-разработки.
  - Неупорядоченный список (`<ul>` из 5 пунктов): основные веб-технологии.
- **Карточка профиля:** Картинка `avatar.svg` с `alt`, имя (**Zhassyn Zhalynuly**), группа (**SE-24 &bull; Astana IT University**), описание и напарники (**Mardan Khalilov**, **Raiymbek Maksotov**).
- **CSS Селекторы (3 типа):**
  1. *Селекторы элементов:* `body`, `h1`, `h2`, `p`, `a`, `ol`, `ul`, `li`.
  2. *Селекторы классов:* `.container`, `.navbar`, `.btn`, `.team-box`, `.list-card`.
  3. *Селекторы ID:* `#main-header`, `#hero`, `#profile`, `#main-footer`.
- **CSS Box Model:** `margin`, `padding`, `border`, `border-radius`, `box-sizing: border-box`.
- **Ссылки:** Эффект наведения `a:hover`.

### 🔹 Task 2: Page Layout Using `<div>` + Floats (`task2.html`, `css/task2.css`)
- **Строгое условие:** **Без Flexbox (`display: flex`) и без Grid (`display: grid`)**.
- **Разделы:**
  - *Header:* Заголовок и подзаголовок страницы.
  - *Navbar:* Ссылки на все задания на `display: inline-block`.
  - *Sidebar:* Меню слева (`float: left; width: 26%;`).
  - *Content:* Основной блок справа (`float: right; width: 71%;`).
  - *Clearfix:* Разделитель с `clear: both;` (защита от схлопывания).
  - *Footer:* Нижний колонтитул с авторскими правами.

### 🔹 Task 3: Tribute Page &mdash; Alan Turing (`exercise1/index.html`, `css/task3.css`)
- Создан в папке `exercise1/` согласно Step 0.
- Заголовок `<h1>`, подзаголовок `<h2>`, годы жизни `1912 – 1954`.
- Краткая биография (жизнь, дешифровка Энигмы, машина Тьюринга).
- Списки: `<ol>` с 6 хронологическими датами и `<ul>` с 5 ключевыми изобретениями.
- Портрет `<img>` с `alt` и рамкой.
- Кнопка `.btn` ("Learn more on Wikipedia") и ссылки.
- Шрифты Google Fonts: `Cinzel` для заголовков и `Arial` для текста.

### 🔹 Task 4: CSS Table and Feedback Form (`task4.html`, `css/task4.css`)
- **Таблица оценок:**
  - Студенты: **Zhassyn Zhalynuly**, **Mardan Khalilov**, **Raiymbek Maksotov**.
  - Границы всех ячеек и схлопывание: `border-collapse: collapse;`.
  - Цвет шапки: `th { background-color: #0066cc; color: white; }`.
  - Чередование строк зеброй: `tbody tr:nth-child(even)`.
  - Выделенная строка: `.highlight-row { background-color: #ffff99; }`.
  - Выравнивание текста по центру: `text-align: center;`.
  - Объединение ячеек: `rowspan="3"` (кафедра) и `colspan="3"` (итог).
  - Заголовок с ID: `#table-heading`.
- **Форма обратной связи:**
  - Центрирована на странице с фиксированной шириной: `#feedback-form { max-width: 480px; margin: 0 auto; }`.
  - Жирные подписи: `label { font-weight: bold; }`.
  - Поля: Text (имя), Email (почта), Select (роль), Radio (Yes/No), Textarea (комментарии), Submit (кнопка).
  - Кнопка с фоном, скруглением и hover-эффектом (`.btn-submit`).

### 🔹 Task 5: Midterm Project Topic & Wireframes (`task5.html`, `css/task5.css`)
- **Тема проекта:** **DevSphere &mdash; Student Developer &amp; Project Showcase Platform**.
- **Описание (3–5 предложений):** Студенческая платформа проектов AITU, цель, целевая аудитория.
- **Команда:** Zhassyn Zhalynuly, Mardan Khalilov, Raiymbek Maksotov.
- **Карта сайта (Sitemap):** Четкая иерархия страниц (Header &rarr; 5 Pages &rarr; Footer).
- **5 вайрфреймов:**
  1. *Page 1: Home / Landing*
  2. *Page 2: Projects Catalog & Filter*
  3. *Page 3: Project Details Page*
  4. *Page 4: Student Community Directory*
  5. *Page 5: Contact & Support Page*

---

## 🎯 Шпаргалка для устной защиты (Oral Defense Cheat Sheet)

1. **Что такое CSS Box Model?**
   - Это блочная модель: любой элемент состоит из содержимого (`content`), внутренних отступов (`padding`), рамки (`border`) и внешних отступов (`margin`).
   - `box-sizing: border-box;` включает `padding` и `border` в общую ширину элемента, чтобы он не растягивался шире положенного.

2. **В чем разница между селекторами (Element, Class, ID)?**
   - **Element** (`p`, `h1`): стилизует все такие теги на странице.
   - **Class** (`.btn`, `.card`): можно вешать на много разных элементов, пишется через точку.
   - **ID** (`#main-header`, `#feedback-form`): уникальный на странице, пишется через `#`, имеет наибольший приоритет.

3. **Как работает float и зачем нужен clearfix (Task 2)?**
   - `float: left` и `float: right` сдвигают блоки к краям родителя.
   - Из-за этого родитель "не видит" высоту плавающих блоков и схлопывается в 0.
   - Блок с `clear: both;` (clearfix) отменяет обтекание и возвращает родителю нормальную высоту.

4. **Как объединять ячейки в таблице (Task 4)?**
   - `rowspan="3"` — объединение 3 строк по вертикали.
   - `colspan="3"` — объединение 3 столбцов по горизонтали.
   - `border-collapse: collapse;` — схлопывает двойные рамки ячеек в аккуратные одинарные.
   - `:nth-child(even)` — задает цвет каждой четной строке таблицы.

5. **Как связываются label и input в форме?**
   - Через `for` у `<label>` и `id` у `<input>`. При клике на текст метки курсор сразу активирует нужное поле.