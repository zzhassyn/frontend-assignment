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

```text
frontend-assignment/
├── index.html                   # Task 1: Personal Webpage & Introduction to HTML/CSS
├── styles.css                   # Task 1: Element, Class, ID selectors & CSS Box Model
├── task2.html                   # Task 2: Page Layout using <div> + Floats (No Flexbox / No Grid)
├── task2.css                    # Task 2: float: left, float: right, clear: both
├── exercise1/                   # Task 3: Tribute Page folder (per assignment specification)
│   ├── index.html               # Task 3: Alan Turing Tribute HTML
│   └── styles.css               # Task 3: Google Fonts, image styling, lists, buttons
├── task3.html                   # Task 3 root alias / redirect to exercise1/index.html
├── task4.html                   # Task 4: CSS Table (Student Grades) & Feedback Form
├── task4.css                    # Task 4: Table (:nth-child, .highlight-row, colspan/rowspan) & Form
├── task5.html                   # Task 5: Midterm Project (DevSphere) Topic, Sitemap & 5 Wireframes
├── task5.css                    # Task 5: Sitemap structure & Wireframe viewer
├── images/                      # Media assets & SVG blueprints
│   ├── avatar.svg               # Profile avatar illustration
│   ├── alan_turing.svg          # Alan Turing tribute portrait illustration
│   └── wireframes/              # 5 Low-fidelity architectural wireframe diagrams
│       ├── page1_home.svg       # Page 1: Home / Landing wireframe
│       ├── page2_projects.svg   # Page 2: Projects Catalog & Filter wireframe
│       ├── page3_details.svg    # Page 3: Project Details & Team collaboration wireframe
│       ├── page4_community.svg  # Page 4: Student Community Directory wireframe
│       └── page5_contact.svg    # Page 5: Contact & Support wireframe
├── assignment1_frontend.docx    # Original assignment prompt document
└── README.md                    # Project documentation & defense preparation guide
```

---

## 📋 Task Overview & Requirements Fulfillment

### 🔹 Task 1: Introduction to HTML & CSS (`index.html`, `styles.css`)
- **HTML:** Semantic hierarchy (`<header id="main-header">`, `<main>`, `<section>`, `<h1>`, `<h2>`, `<p>`).
- **Lists:**
  - Ordered List (`<ol>` with 5 items): Chronological web development milestones.
  - Unordered List (`<ul>` with 5 items): Core web technologies and tools.
- **Profile Card:** Image (`<img>` with `alt`), student name (**Zhassyn Zhalynuly**), group (**SE-24 &bull; Astana IT University**), description, and team members (**Mardan Khalilov**, **Raiymbek Maksotov**).
- **CSS Selectors (3 required types):**
  1. *Element Selectors:* `body`, `h1`, `h2`, `p`, `a`, `ol`, `ul`, `li`, `img`.
  2. *Class Selectors:* `.container`, `.navbar`, `.profile-card`, `.list-card`, `.btn`.
  3. *ID Selectors:* `#main-header`, `#hero`, `#profile`, `#main-footer`.
- **CSS Box Model:** `margin`, `padding`, `border`, `border-radius`, `box-sizing: border-box`.
- **Links:** Clickable links with hover effect (`a:hover`).

### 🔹 Task 2: Page Layout Using `<div>` + Floats (`task2.html`, `task2.css`)
- **Strict Constraint:** **NO Flexbox (`display: flex`) and NO Grid (`display: grid`)**.
- **Layout Sections:**
  - *Header:* Website title and tagline.
  - *Navigation Bar:* Links to all 5 tasks using `display: inline-block`.
  - *Sidebar Menu (Left):* `float: left; width: 28%;`, with menu links and callout box.
  - *Main Content (Right):* `float: right; width: 68%;`, with headings and paragraphs explaining float and clear.
  - *Clearfix:* Clear element with `clear: both;` ensuring zero container collapse.
  - *Footer:* Full-width bottom bar with copyright text.

### 🔹 Task 3: Tribute Page &mdash; Alan Turing (`exercise1/index.html`, `exercise1/styles.css`)
- **Folder:** Created in dedicated `exercise1/` directory.
- **Content:**
  - Main heading `<h1>Alan Mathison Turing</h1>`, subheading `<h2>About Alan Turing</h2>`, birth/death tagline `<h3>`.
  - Summary paragraph (3–5 sentences) about Turing's life, Enigma codebreaking, and computing theories.
  - Ordered list (`<ol>`): 6 chronological milestones.
  - Unordered list (`<ul>`): 5 key inventions and contributions.
  - Portrait `<img>` with descriptive `alt` attribute.
  - Clickable links and a styled `.btn` ("Learn more on Wikipedia").
- **CSS (Step 4):**
  - Page background color.
  - Two Google Fonts linked: `Cinzel` (headings) and `Plus Jakarta Sans` (body).
  - Header: background, text color, padding, center alignment.
  - Container `.content`: `max-width: 800px; margin: 0 auto; padding: 30px 15px;`.
  - Image: `max-width`, `border-radius`, `box-shadow`, `border`.
  - Headings, paragraphs, lists (`list-style-type`, spacing), and `.btn` hover effect.

### 🔹 Task 4: CSS Table and Feedback Form (`task4.html`, `task4.css`)
- **Table Styling:**
  - Student grades table featuring **Zhassyn Zhalynuly**, **Mardan Khalilov**, and **Raiymbek Maksotov**.
  - Background color on table header (`th`) and borders for all cells (`border-collapse: collapse;`).
  - Alternate row striping using `tr:nth-child(even)`.
  - Highlighted row with distinct background color using `.highlight-row`.
  - Center-aligned cell text (`text-align: center`).
  - Merged cells: `rowspan="3"` for Department and `colspan="3"` for summary average row.
  - Page heading above table with an ID selector (`#table-heading`).
- **Feedback Form:**
  - Centered on page with `max-width: 520px; margin: 0 auto;`, background color, padding, and rounded corners (`#feedback-form`).
  - Bold styled `<label>` elements (`font-weight: bold;`).
  - Form fields: Text (Name), Email (Address), Select dropdown (Academic Role), Radio buttons (Yes/No recommendation), Textarea (Comments), Submit button.
  - Submit button with background color, rounded corners, and hover effect.
  - ID and Class selectors used: `#form-heading`, `#feedback-form`, `#btn-submit`, `.form-group`, `.btn-submit`.

### 🔹 Task 5: Midterm Project Topic & Wireframes (`task5.html`, `task5.css`)
- **Group Project Topic:** **DevSphere &mdash; Student Developer &amp; Project Showcase Platform**.
- **Project Description (3–5 sentences):** Explains the topic, target users (AITU software engineering students), and purpose (portfolio showcase, teammate recruitment, open project repository).
- **Group Authors:** Zhassyn Zhalynuly, Mardan Khalilov, Raiymbek Maksotov.
- **Sitemap:** Hierarchical navigation structure showing how all 5 pages link together under the persistent header and footer.
- **5 Low-Fidelity Wireframes Designed & Embedded:**
  1. *Page 1: Home / Landing Page* &mdash; Hero banner, CTA buttons, 3-column project cards, metrics counter.
  2. *Page 2: Projects Catalog* &mdash; Search bar, category filter sidebar, 2-column project grid, pagination.
  3. *Page 3: Project Details Page* &mdash; Screenshot gallery placeholder, tech tags, demo/repo links, team roster, join form.
  4. *Page 4: Student Community Directory* &mdash; Search header, major filter, developer cards with skill badges.
  5. *Page 5: Contact & Support Page* &mdash; Inquiry form, campus office hours, FAQ section.

---

## 🎯 Шпаргалка для устной защиты (Oral Defense Cheat Sheet)

На устной защите преподаватель может задать вопросы по коду. Вот простые и четкие ответы:

1. **Что такое CSS Box Model (Блочная модель)?**
   - Каждый HTML-элемент браузер представляет как прямоугольный блок, состоящий из 4 слоев:
     1. `content` — содержимое (текст, картинка).
     2. `padding` — внутренний отступ от содержимого до рамки.
     3. `border` — рамка вокруг элемента.
     4. `margin` — внешний отступ от элемента до соседних блоков.
   - `box-sizing: border-box;` заставляет браузер включать `padding` и `border` в общую ширину (`width`), чтобы элементы не вылезали за пределы экрана.

2. **Чем отличаются селекторы (Element, Class, ID)?**
   - **Element selector** (`p`, `h1`, `a`): применяет стили ко всем тегам этого типа на всей странице.
   - **Class selector** (`.profile-card`, `.navbar`): можно применять к нескольким элементам, начинается с точки.
   - **ID selector** (`#main-header`, `#feedback-form`): уникальный идентификатор, применяется только к одному конкретному элементу на странице, имеет более высокий приоритет (специфичность), начинается с решетки `#`.

3. **Как работает `float` и зачем нужен `clear: both` (clearfix) во 2 задании?**
   - `float: left` и `float: right` сдвигают блоки влево и вправо, выводя их из нормального потока документа.
   - Из-за этого родительский блок "теряет" высоту своих плавающих детей и схлопывается в 0.
   - Элемент с `clear: both;` (clearfix) отменяет обтекание и заставляет родительский контейнер полностью растянуться на высоту колонок.

4. **Как объединять ячейки в таблице (Task 4)?**
   - `rowspan="3"` — объединяет 3 строки по вертикали (у нас объединяет ячейку кафедры Computer Science).
   - `colspan="3"` — объединяет 3 столбца по горизонтали (у нас объединяет итоговую строку среднего балла).
   - `border-collapse: collapse;` — убирает двойные расстояния между ячейками и делает аккуратные одинарные границы.
   - `:nth-child(even)` — автоматически красит четные строки таблицы другим цветом (эффект зебры).

5. **Как связаны `<label>` и `<input>` в форме?**
   - Атрибут `for` у `<label>` должен в точности совпадать с атрибутом `id` у соответствующего `<input>`. При клике на текст метки курсор автоматически встает в поле ввода, что важно для доступности (accessibility).