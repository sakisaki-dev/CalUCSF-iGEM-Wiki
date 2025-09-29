# 🧬 CalUCSF NeuroSplice iGEM 2025 Wiki Source Code

This repository contains the complete source code for the **CalUCSF iGEM 2025** team's official wiki, built entirely as a single, standalone HTML file.

---

## 🔬 Project Overview: NeuroSplice

**NeuroSplice** is a synthetic biology project focused on developing a **low-cost, paper-based diagnostic platform** for neurological diseases such as **Multiple Sclerosis (MS)**.

Our system utilizes **toehold switches** within a **cell-free transcription-translation (TX-TL) system** to specifically detect disease-associated RNA splicing variants (e.g., the **IL7R exon 6 skip**).  
The goal is to provide a **highly specific, accessible, and contained diagnostic tool** that eliminates the need for complex lab infrastructure.

---

## ✨ Key Features of the Wiki

The wiki is designed as a single-page, fully responsive site with modern web features:

- **Responsive Layout**: Optimized for mobile and desktop.
- **Sticky Navigation**: Includes a scroll-progress bar for easier reading.
- **Tabbed Sections**: Organized tabs for **Project**, **Wet Lab**, and **Human Practices**.
- **Interactive DBTL Loop**: A dedicated section demonstrating the **Design-Build-Test-Learn** cycle with a liquid-filling pipette animation tied to scroll position.
- **Styling**: Custom design based on **UC Berkeley** and **UCSF** colors, implemented with **Tailwind CSS**.

---

## 💻 Technical Stack

| Component     | Technology        | Purpose |
|---------------|------------------|---------|
| **Structure** | HTML5            | Single-page architecture (`landing.html`). |
| **Styling**   | Tailwind CSS     | Utility-first CSS framework (via CDN). |
| **Interactivity** | Vanilla JavaScript | Scroll animations, tab logic, DBTL interactivity. |
| **Typography** | Inter Font      | Modern, readable sans-serif font. |

---

## 🚀 Local Setup and Deployment

Since the entire wiki is contained within a single file, deployment is very simple.

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/YourUsername/your-repo-name.git
