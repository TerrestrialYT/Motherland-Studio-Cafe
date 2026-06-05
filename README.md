# 🌿 Motherland Cafe - Digital Menu & Website

A fast, fully responsive, and elegant single-page website built for **Motherland Cafe**. This project features a dynamic dual-location menu system, strict aesthetic guidelines, and built-in local SEO optimization.

Everything is built completely from scratch using pure static HTML, Tailwind CSS, and vanilla JavaScript to ensure maximum speed and minimal overhead.

---

### 🚀 Features

*   **Dual-Location Toggle UI:** A vanilla JavaScript-powered pill toggle that instantly swaps the menu interface between the **Kyd Street** and **Southern Avenue** branches.
*   **Dynamic Footer:** Automatically updates the physical address, timings, and contact information based on the currently selected location.
*   **Sticky WhatsApp CTA:** A floating, always-accessible button linking directly to the cafe's WhatsApp (`+91 97480 77790`) for quick orders and reservations.
*   **Advanced Local SEO:** Embeds dual JSON-LD Schema Markups in the `<head>`, indexing both restaurant locations individually for search engines.
*   **Responsive Masonry/Grid Layout:** Clean, overlapping hero elements and soft rounded corners that look flawless on both desktop and mobile devices.

---

### 🎨 Design System & Aesthetics

The UI adheres to a strict visual aesthetic designed to evoke a warm, natural, and premium cafe experience.

**Color Palette:**
*   🟢 **Primary Background:** Deep Olive / Sage Green (`#525A4B`)
*   ⚪ **Menu Background:** Warm Cream / Off-White (`#FDFCF0`)
*   🟤 **Accents & Buttons:** Warm Sand / Beige (`#D5C7B5`)

**Typography:**
*   **Headings:** `Playfair Display` or `Cinzel Decorative` (Elegant, decorative serif)
*   **Body:** `Inter` (Clean, highly legible sans-serif)

---

### 🛠️ Tech Stack

*   **HTML5:** Semantic, strictly structured static markup.
*   **Tailwind CSS (via CDN):** Rapid, utility-first styling without the need for a build step.
*   **Vanilla JavaScript:** Lightweight DOM manipulation for the menu toggles and dynamic text updates (`toggleLocation()` function).

---

### 📂 Architecture Overview

The core logic of the site revolves around two main DOM containers that hold the extensive menus for each branch:

1.  `<div id="menu-kyd">`: The default view containing the Kyd Street offerings (e.g., House Brewed Kombucha, All Day Eggs, Buckwheat Crepes, Handrolled Pastas).
2.  `<div id="menu-southern" class="hidden">`: The secondary view containing the Southern Avenue offerings (e.g., Vegan Smoothies, Tartines, Turkiye Meze Bar, Guilt-Free Desserts).

The JavaScript listens for the toggle click, applies/removes Tailwind's `hidden` class on these containers, and synchronizes the footer data to match.

---

### 💻 Installation & Usage

Because this project is built with static HTML and a Tailwind CDN, there is no complex build pipeline or package manager required. 

1. Clone the repository to your local machine.
2. Open `index.html` in any modern web browser.
3. Edit the HTML directly to update menu items, prices, or SEO schemas.

---
*Designed and built by [Terrestrial][(https://github.com/TerrestrialYT](https://terrestrialyt.com/)).*
