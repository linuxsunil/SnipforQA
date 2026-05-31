# 🎥 SnipForQA Studio 🚀
### *Eliminating the fragmented headache of e-learning video & visual compliance reviews.*

👉 **[Click Here to Launch the Live App Instantly!](https://linuxsunil.github.io/SnipforQA/)**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License: MIT](https://img.shields.io/badge/License-MIT-pink.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

---

## 💡 The Problem & The Inspiration

As an **Instructional Designer**, I love building high-impact learning experiences—but I *dread* the traditional QA process. 

Before building this tool, a typical review loop for a multi-minute e-learning video or interactive module looked like this:
1. Watch the course/video until you spot a bug (overlapping text, branding error, audio sync issue).
2. Take a screenshot via a desktop snippet tool.
3. Open an image editor, draw red boxes or arrows, and save it locally.
4. Open **Jira**, **Asana**, or an Excel tracker, type out the description, manually type the video timestamp, and upload the image.
5. Repeat this 45 times per course. 😫

**SnipForQA** was born over a single weekend to completely eliminate this friction. It brings the video player, snapshot utilities, robust canvas annotation vectors, and database logging into a **single, serverless browser panel**. When you are done, it compiles an enterprise-grade **Excel Defect Log with all annotated screenshots natively embedded into the sheet rows.**

---

## ✨ Key Features

### 🎬 1. Native Video Tab & Auto-Timestamp Tracking
* Drag and drop your target e-learning video directly into the interface (processed locally—your media never leaves your computer).
* The moment you hit **Pause** to inspect a visual defect, the system **instantly auto-stamps the precise timeline timecode** straight into the issue tracker array.
* Take a point-in-time frame screenshot natively with a single click.

### 🖼️ 2. Dynamic Screenshot Annotation Canvas
* Working in an external platform like Articulate Rise, Storyline, or a legacy LMS? Hit your system hotkey (`Win+Shift+S` or `Cmd+Shift+4`), drop back into the app, and hit **`Ctrl + V`**.
* The image loads instantly onto an interactive HTML5 canvas allowing you to immediately sketch **rectangles, arrows, freehand lines, or floating text highlights** with customizable stroke widths and semantic colors.

### 📊 3. JSZip / SheetJS Automated Excel Compiling Engine
* Ditch the manual formatting. Enter project metadata and click **Export**.
* The app programmatically parses the JavaScript object array, generates a strict workbook structure, dynamically updates cell sizing specifications, and maps raw base64 graphics directly into the `xl/drawings/drawing1.xml` OpenXML schema.

---

## 🛠️ Tech Stack & Micro-Architecture

This app functions entirely client-side. No databases, no hidden servers, and completely self-contained. 

* **Core UI:** Vanilla HTML5, semantic layout trees using CSS Grid/Flexbox, and adaptive design leveraging the **DM Sans** & **DM Mono** font scales.
* **Data Serialization:** [SheetJS (xlsx.full.min.js)](https://github.com/SheetJS/sheetjs) handles base spreadsheet manipulation.
* **OpenXML Packaging:** [JSZip](https://stuk.github.io/jszip/) allows the app to unzip raw Excel binary streams, inject contextual media drawing anchors (`drawing1.xml.rels`), map compression arrays, and repackage it as an `.xlsx` download.

---

## 🔮 Future Roadmap: AI & OCR Integration

Because I am focused on using AI and advanced tech layers to destroy tedious instructional design tasks, the next generation of this toolkit will include:
* **Tesseract.js OCR Automation:** When pasting generic raw snapshots from windows, the system will look for common media player timestamp positioning, read the pixels using OCR, and extract/auto-fill the timecode without requiring a dedicated video import file.
* **Gemini Flash Visual Compliance Auditing:** Integrating lightweight multimodal endpoints to scan video files against a strict branding layout style guide to auto-generate the defect logs entirely.

---

## 🚀 Getting Started

Since this is a lightweight frontend workspace, running it requires zero terminal command configuration:

1. Clone the repository:
```bash
   git clone [https://github.com/linuxsunil/SnipforQA.git](https://github.com/linuxsunil/SnipforQA.git)