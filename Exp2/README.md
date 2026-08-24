# WDL Experiment 2: Design Web Portal Using CSS3

## 📌 Project Overview
**Course:** Web Development Laboratory (316U01L306)  
**Semester:** III  
**Institution:** K. J. Somaiya School of Engineering (Somaiya Vidyavihar University)  
**Use Case:** AI-based Smart Irrigation Advisory System (`KJS-AGR-01`)

---

## 🎯 Experiment Tasks & Features
1. **Task 1: Inline CSS Header** — Custom header styling directly on elements (`<h1>`, `<p>`, `<header>`).
2. **Task 2: Internal CSS Navigation** — Horizontal navigation bar with hover effects using `<style>` in `<head>`.
3. **Task 3: External CSS Website Theme** — Site-wide theming, font families, and footer styles defined in `style.css`.
4. **Task 4: Categories & System Alerts Sidebar** — Rounded cards with box shadows and interactive list hover effects.
5. **Task 5: Card Layout with CSS Box Model** — Structured information cards utilizing margins, paddings, borders, and shadows.
6. **Task 6: Image / Feature Grid Gallery** — Interactive sensor grid with CSS hover zoom transitions (`transform: scale(1.05)`).
7. **Task 7: Data Table Styling (`table.css`)** — Telemetry and rate cards with `border-collapse`, `nth-child(even)` zebra-striping, and centered alignments.
8. **Task 8: Registration Form (`form.css`)** — Clean form UI featuring fieldsets, legends, `:focus` glows, and button `:hover` effects.
9. **Task 9: Page Layout (`layout.css`)** — Two-column responsive layout built using CSS Flexbox.
10. **Task 10: CSS Animations & Highlighting** — Glowing alert highlights powered by `@keyframes` animations and `box-shadow`.

---

## 📂 File Structure
```text
Exp2/
├── index.html        # Main homepage (Header, Nav, Alert highlight, 2-column layout)
├── farm_info.html    # Farm info, workflow steps, sensor grid & crop stages
├── advisory.html     # Real-time AI irrigation advisory report
├── sensor_data.html  # Live telemetry & equipment price list tables
├── contact.html      # Farmer registration and query form
├── book.html         # Agricultural reference guides & book cards
├── style.css         # Global website theme and footer styles
├── layout.css        # Flexbox page layout (Content & Sidebar)
├── table.css         # Table border-collapse & zebra-striping
├── form.css          # Form inputs, fieldset & focus states
└── README.md         # Project documentation
```

---

## 🚀 How to Run Locally
1. Double-click on `index.html` to open it in your browser.
2. Or run a local HTTP server:
   ```bash
   python -m http.server 8000
   ```
   and navigate to `http://localhost:8000/index.html`.
