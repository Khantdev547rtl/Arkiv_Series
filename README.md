<div align="center">

# 🎓 A R K I V
### *The Present Simple* — Digital Reading Room & Series Showcase

[![Team](https://img.shields.io/badge/Team-Arkiv-476053?style=for-the-badge&logo=bookstack&logoColor=white)](mailto:arkiv0110@gmail.com)
[![Contact](https://img.shields.io/badge/Contact-arkiv0110%40gmail.com-364B40?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arkiv0110@gmail.com)
[![Level](https://img.shields.io/badge/CEFR_Level-A1_%E2%80%93_A2%2B-88A899?style=for-the-badge)](#)
[![Architecture](https://img.shields.io/badge/Build-Zero_Dependency_SPA-24221E?style=for-the-badge)](#)

*Unhurried study, quiet structure, and enduring practice.*

[Explore the Philosophy](#-philosophy--aesthetic) • [Key Features](#-key-features) • [The 8-Volume Catalog](#-the-8-volume-catalog) • [Technical Architecture](#-technical-architecture)

</div>

---

## 🌿 Philosophy & Aesthetic

The **Arkiv Educational Series Showcase** is a calm, low-glare, introvert-friendly digital reading room designed for *The Present Simple* curriculum. 

Traditional learning platforms rely on noisy notifications, streaks, leaderboards, and countdown timers that create anxiety. **Arkiv** takes the opposite approach—replacing pressure with quiet shelf marks, tactile 3D page-turning physics, and warm, low-contrast reading atmospheres tailored for deep, uninterrupted focus.

---

## ✨ Key Features

| Feature | Experience & Design |
| :--- | :--- |
| **📖 True 3D Flipbook Reader** | Renders live Google Drive PDFs directly inside an interactive 3D spread using **PDF.js** and **St.PageFlip**. Drag page corners or use arrow keys to turn pages naturally. |
| **🕯️ Three Quiet Atmospheres** | Switch seamlessly between **Paper** (warm archival linen `#F6F3EC`), **Dusk** (soft slate twilight `#22262B`), and **Lamp** (deep midnight forest `#0F1722`) to eliminate eye strain. |
| **🔖 Private Shelf Marks** | Silently mark volumes as *Unread*, *Currently Reading*, or *Completed*, and toggle bookmarks saved privately in your browser's `localStorage`. |
| **⏱️ Quiet Reading Pace View** | An isolated, distraction-free reading column with customizable line spacing (*Relaxed*, *Airy*, *Slow*), column measure (*Narrow*, *Wide*), and a gentle, non-intrusive session guide. |
| **🗺️ Curated Reading Paths** | Follow guided study sequences tailored to your learning style: **Story First**, **Vocabulary First**, or **Exam Prep First**. |
| **🔍 Cross-Edition Lookup** | Instantly search across 135 story chapters and core vocabulary words (e.g., *archive*, *routine*, *debug*, *schedule*) to locate their exact edition and chapter source. |

---

## 📚 The 8-Volume Catalog

| Vol. | Title | Category | Scope & Structure | Level |
| :---: | :--- | :--- | :--- | :---: |
| **01** | **The Present Simple: First Edition** | `Textbook` | 35 story-driven chapters, grammar reference, final practice exam & answer key | `A1–A2` |
| **02** | **The Present Simple: Second Edition** | `Textbook` | 50 original everyday & workplace chapters, grammar notes & progress tests | `A1–A2+` |
| **03** | **The Present Simple: Third Edition** | `Textbook` | 50 structured chapters with Reading Check, Grammar, Writing & Speaking tasks | `A1–A2+` |
| **04** | **The Present Simple: Final Edition** | `Capstone` | 135-chapter synthesis, 15-point Error Clinic, 4 Reading Labs & 100 mock items | `A1–A2+` |
| **05** | **Master Vocabulary & Practice Book** | `Vocabulary` | Complete V1, V2, V3 & V-ing verb tables, noun/adjective lists & 100+ questions | `A1–A2` |
| **06** | **Companion Vocabulary Book** | `Vocabulary` | Consolidated word lists & A–Z cross-reference index across all 135 chapters | `A1–A2` |
| **07** | **Master Examination (300 Marks)** | `Assessment` | 300-mark exam across 6 formats: MCQs, verb/word forms, initials & dialogue | `A1–A2+` |
| **08** | **300-Question Multiple-Choice Exam** | `Assessment` | 300 single-mark multiple-choice items (`300 × 1 = 300 Marks`) & full key | `A1–A2+` |

---

## 🛠️ Technical Architecture

Designed as a self-contained, portable Single-Page Application (SPA) requiring zero build steps or backend servers:

* **Core Structure:** Semantic HTML5 & Vanilla JavaScript (ES6+)
* **Styling & Layout:** Tailwind CSS (CDN) + Custom CSS Variables for dynamic theme switching
* **Typography:** [Newsreader](https://fonts.google.com/specimen/Newsreader) (editorial serif) & [Inter](https://fonts.google.com/specimen/Inter) (clean UI sans-serif)
* **3D PDF Engine:** [Mozilla PDF.js](https://mozilla.github.io/pdf.js/) (`v2.16.105`) paired with [St.PageFlip](https://nodlik.github.io/St.PageFlip/)
* **Persistence:** Client-side `window.localStorage` (`arkiv_quiet_shelf_v1`)

---

## 🚀 Quick Start

1. **Download** `index.html` from this repository.
2. **Open** the file directly in any modern web browser (Chrome, Safari, Firefox, Edge).
3. **Read & Explore:**
   * Click **Read Book** on any volume card to launch the 3D flipbook reader *(requires an active internet connection to fetch PDF streams from Google Drive)*.
   * Switch to **Reading Pace** in the top navigation bar for offline excerpt reading and pacing.

---

<div align="center">

**Imprint & Colophon**  
Published by **Team Arkiv** • Inquiries: [arkiv0110@gmail.com](mailto:arkiv0110@gmail.com)  
*Designed for quiet, enduring practice.*

</div>
