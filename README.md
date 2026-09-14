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

A shared, interactive top navigation bar (`navbar`) connects all 5 tasks across separate pages.

---

## 📁 Repository Structure

```text
frontend-assignment/
├── index.html                   # Task 1: Personal Webpage & Introduction to HTML/CSS (GitHub Pages Root)
├── styles.css                   # Task 1: CSS styling (Element, Class, ID selectors, Box Model)
├── task2.html                   # Task 2: Page Layout using <div> + positioning/floats (Zero Flex/Grid)
├── task2.css                    # Task 2: CSS styling (float: left, float: right, clearfix)
├── exercise1/                   # Task 3: Tribute Page folder (per assignment specification)
│   ├── index.html               # Task 3: Alan Turing Tribute HTML
│   └── styles.css               # Task 3: Google Fonts, image styling, lists, buttons
├── task3.html                   # Task 3 root alias / redirect to exercise1/index.html
├── task4.html                   # Task 4: CSS Table (Student Grades) & Course Feedback Form
├── task4.css                    # Task 4: CSS styling (nth-child, highlight-row, colspan/rowspan, form)
├── task5.html                   # Task 5: Midterm Project (DevSphere) Topic, Sitemap & 5 Wireframes
├── task5.css                    # Task 5: CSS styling (Sitemap tree, wireframe viewer, responsive cards)
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
└── README.md                    # Project documentation, instructions & defense preparation
```

---

## 📋 Detailed Task Breakdown & Requirements Fulfillment

### 🔹 Task 1: Introduction to HTML & CSS (`index.html`, `styles.css`)
- **HTML Structure:** Semantic hierarchy with `<header id="main-header">`, `<main>`, `<section>`, `<h1>`, `<h2>`, `<h3>`, and informative paragraphs.
- **Lists Included:**
  - Ordered List (`<ol>` with 5 items): Chronological web development milestones.
  - Unordered List (`<ul>` with 5 items): Core web technologies and toolchains.
- **Profile Card:** Dedicated card containing portrait image (`<img>` with descriptive `alt`), student name (**Zhassyn Zhalynuly**), team roster (**Mardan Khalilov**, **Raiymbek Maksotov**), university credentials, and bio.
- **Links & Images:** Multiple clickable external links (`<a>` with animated hover effects) and optimized SVG avatar with `border-radius: 50%` and `max-width`.
- **CSS Selectors Required:**
  - *Element Selectors:* `body`, `h1`, `h2`, `p`, `a`, `ol`, `ul`, `li`, `main`, `footer`.
  - *Class Selectors:* `.profile-card`, `.nav-link`, `.btn-primary`, `.badge-pill`, etc.
  - *ID Selectors:* `#main-header`, `#hero-banner`, `#profile-section`, `#main-footer`.

### 🔹 Task 2: Page Layout Using `<div>` + Floats & Positioning (`task2.html`, `task2.css`)
- **Strict Architectural Constraint:** **NO CSS Flexbox (`display: flex`) and NO CSS Grid (`display: grid`)**.
- **Layout Sections:**
  - *Header:* Website title and tagline.
  - *Navigation Bar:* 5 navigation links linking all tasks.
  - *Sidebar Menu (Left):* `float: left; width: 28%`, containing 5 menu links and an informational callout box.
  - *Main Content / Aside (Right):* `float: right; width: 68%`, featuring headers, paragraphs, and quote badges.
  - *Clearfix:* Clear element with `clear: both;` ensuring zero parent container collapse.
  - *Footer:* Full-width bottom bar with `clear: both;` and copyright text.

### 🔹 Task 3: Tribute Page &mdash; Alan Turing (`exercise1/index.html`, `exercise1/styles.css`)
- **Step 0:** Created in dedicated `exercise1/` folder with linked `styles.css` (also accessible via `task3.html`).
- **Step 1:** Main heading `<h1>Alan Mathison Turing</h1>`, subheading `<h2>About Alan Turing</h2>`, birth/death tagline `<h3>`, and a 5-sentence biographical summary.
- **Step 2:**
  - Ordered List (`<ol>`): 6 major chronological milestones (Cambridge fellowship, Turing Machine paper, Bletchley Park Enigma codebreaking, ACE computer, Turing Test, Morphogenesis).
  - Unordered List (`<ul>`): 5 key inventions & scientific breakthroughs.
- **Step 3:** Portrait `<img>` with descriptive `alt` attribute, multiple links, and a styled `.btn-wikipedia` ("Learn More on Wikipedia").
- **Step 4 CSS Styling:**
  - Gradient dark theme background (`#0f172a` to `#1e293b`).
  - Google Fonts integrated: `Cinzel` (classical serif for headings) and `Plus Jakarta Sans` (sans-serif for body).
  - Styled `.content` container with `max-width: 860px; margin: 0 auto; padding: 3rem 1.5rem;`.
  - Image with `border-radius: 16px;`, glowing box-shadow, and hover scale micro-interaction.

### 🔹 Task 4: CSS Tables and Feedback Form (`task4.html`, `task4.css`)
- **Part 1: Student Grades Table:**
  - Columns: Department, Student Full Name, Course Subject, Assignment Score, Final Letter Grade, Academic Status.
  - Rows: Features team members **Zhassyn Zhalynuly**, **Mardan Khalilov**, and **Raiymbek Maksotov**.
  - Background color on table header (`th`) and solid borders on all cells (`border-collapse: collapse;`).
  - Alternate row striping using `tr:nth-child(even)` and `tr:nth-child(odd)`.
  - Highlighted row with distinct background using `.highlight-row`.
  - Center-aligned cell text (`text-align: center`).
  - Merged cells: `rowspan="3"` for Department and `colspan="3"` for cohort summary row.
  - Custom page heading using ID selector `#table-custom-heading`.
- **Part 2: Interactive Feedback Form:**
  - Centered on page with `max-width: 580px; margin: 0 auto;` with background color, padding, and rounded corners.
  - Bold styled `<label>` elements.
  - Fields included: Text input (Name), Email input (Email), Select dropdown (Role: Student, Teacher, Other), Radio buttons (Yes/No course recommendation), Textarea (Comments), Submit button.
  - Styled submit button with background color, rounded corners, and hover lift effects.
  - CSS includes both `#feedback-form-title`, `#course-feedback-form` (IDs) and `.styled-feedback-form`, `.form-control` (Classes).

### 🔹 Task 5: Midterm Project Specification & Wireframes (`task5.html`, `task5.css`)
- **Group Project Topic:** **DevSphere &mdash; Collaborative Student Developer &amp; Project Showcase Platform**.
- **Project Description (3–5 sentences):**
  > DevSphere is a centralized web platform designed specifically for university software engineering students and student developers at Astana IT University. The target users are undergraduate students seeking portfolio recognition, peer collaborators looking to join ongoing software builds, and faculty mentors monitoring capstone projects. The primary purpose of the website is to streamline student project discovery, provide an open repository for university-wide code showcases, and foster peer-to-peer recruitment across specialized technical disciplines. By integrating detailed project portfolios, member skill matrices, and direct team application workflows, DevSphere elevates student projects from isolated coursework into collaborative campus initiatives.
- **Sitemap Architecture:** Visual navigation tree diagram displaying how all 5 pages link together under the persistent navigation bar and footer.
- **5-Page Low-Fidelity Wireframes Designed &amp; Embedded:**
  1. **Page 1: Home / Landing Page** &mdash; Hero banner, CTA buttons, 3-column featured projects grid, platform metrics counter.
  2. **Page 2: Projects Catalog Page** &mdash; Search bar, category &amp; status filter sidebar, 4-project responsive grid, pagination.
  3. **Page 3: Project Details Page** &mdash; Screenshot gallery placeholder, tech stack badges, live demo/repo links, team roster, and application form.
  4. **Page 4: Student Community Directory** &mdash; Search header, major dropdown, student cards for Zhassyn, Mardan, and Raiymbek with skill badges and profile links.
  5. **Page 5: Contact &amp; Support Page** &mdash; 2-column layout with student inquiry form, university office hours, and FAQ accordion.

---

## 🚀 How to Run Locally

You can run this project locally without any server dependencies:

1. Clone the repository:
   ```bash
   git clone https://github.com/zzhassyn/frontend-assignment.git
   cd frontend-assignment
   ```
2. Open `index.html` in any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari):
   - On Windows: Double-click `index.html` or run:
     ```powershell
     start index.html
     ```
   - Or start a local Python HTTP development server:
     ```bash
     python -m http.server 8000
     ```
     Then open `http://localhost:8000` in your browser.

---

## 🎯 Assignment Oral Defense Preparation Guide

During oral defense at practice lesson time, be ready to explain the following core concepts implemented in our code:

1. **The CSS Box Model:**
   - Every HTML element is modeled as a box consisting of: `content` &rarr; `padding` &rarr; `border` &rarr; `margin`.
   - `box-sizing: border-box;` ensures padding and borders are included within the element's total width and height calculations, preventing unexpected overflow.
2. **CSS Selector Specificity:**
   - Order of specificity: Inline styles (1000) &gt; ID selectors (100) &gt; Class, attribute, and pseudo-class selectors (10) &gt; Element and pseudo-element selectors (1).
   - In Task 1 and Task 4, ID selectors (e.g. `#main-header`, `#table-custom-heading`) uniquely override general class rules.
3. **Float vs. Flexbox (Task 2 vs. Modern Layouts):**
   - In Task 2, `float: left` and `float: right` remove elements from normal block formatting context.
   - The `.clearfix` (`clear: both;`) is mandatory because floated children do not report their height to the parent container, which would otherwise collapse to `height: 0`.
4. **Table Merging Attributes:**
   - `rowspan="3"` merges 3 vertical table rows into a single cell (used for the academic department).
   - `colspan="3"` merges 3 horizontal table columns into a single cell (used for the cohort average summary).
5. **Form Accessibility & Interaction:**
   - The `for` attribute in `<label>` matches the `id` of the `<input>` element, enabling assistive screen readers and expanding the clickable tap target.