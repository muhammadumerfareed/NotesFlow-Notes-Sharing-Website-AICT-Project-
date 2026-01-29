# 📚 NotesFlow

> **Bridging the gap in accessible academic resources through collaborative knowledge sharing.**
> *AICT Web Project*

![Status](https://img.shields.io/badge/Status-Prototype-blue?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Design-Responsive-43A047?style=for-the-badge&logo=mobile)

---

## 🎥 Project Demo

See the platform in action. Click the badges below to explore:

<p align="center">
  <a href="https://muhammadumerfareed.github.io/NotesFlow-Notes-Sharing-Website-AICT-Project-/">
    <img src="https://img.shields.io/badge/WEBSITE-Live_Demo-success?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Live Website"/>
  </a>
  
  &nbsp; &nbsp; <a href="https://www.linkedin.com/posts/muhammad-umer-fareed-675557377_aict-firstsemesterproject-notesflow-activity-7420184068958384128-dDVG?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAF0p8_kB2qk0wf18IejwkPYEZOLWdmhLmVA">
    <img src="https://img.shields.io/badge/WATCH_FULL_DEMO-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Watch on LinkedIn"/>
  </a>
</p>


---

## 📖 Executive Summary

**NotesFlow** is a front-end web prototype designed to democratize access to educational materials. In modern academic environments, quality study resources are often siloed or expensive. NotesFlow solves this by creating a structured, peer-reviewed repository where students can upload lecture notes and access materials from others freely.

This project was built for the **Applications of Information & Communication Technologies (AICT)** course, demonstrating mastery of semantic HTML5 structure, modern CSS3 styling, and responsive user interface design without reliance on external frameworks.

---

## 🎨 Design System & UI Architecture

The interface is built on a custom design system defined in `style.css`, ensuring visual consistency and accessibility.

### Color Palette
| Color | Hex Code | Usage |
| :--- | :--- | :--- |
| **Primary Navy** | `#1a365d` | Headers, Brand Identity, Text Emphasis |
| **Accent Blue** | `#3182ce` | Buttons, Active States, Highlights |
| **Success Green** | `#38a169` | Verification Badges, Feature Lists |
| **Background** | `#f7fafc` | Section Backgrounds (Alternating) |

### Typography
* **Font Family:** `Inter`, sans-serif (Google Fonts)
* **Weights:** 400 (Regular), 500 (Medium), 600 (Semi-Bold), 700 (Bold)
* **Scale:** Modular scale for headings (`2.5rem` to `3rem`) ensuring clear hierarchy.

---

## 🚀 Key Features by Module

### 1. 🏠 Landing Page (`index.html`)
* **Hero Section:** High-conversion layout with dual Call-to-Action (CTA) buttons ("Browse" / "Upload").
* **Live Statistics:** CSS Grid layout displaying platform metrics (15k+ Notes, 8k+ Students).
* **Feature Highlights:** Card-based layout utilizing Flexbox for "Popular Categories" (CS, Math, Physics).

### 2. 🔍 Browse & Discovery (`browse.html`)
* **Smart Search Bar:** Centered input field for filtering content by subject or topic.
* **Note Cards:** Detailed card components displaying:
    * Subject Tags (e.g., "Computer Science")
    * Metadata (Author, Page Count, Last Updated)
    * Direct Download Actions.

### 3. 📤 Submission Engine (`upload.html`)
* **Comprehensive Form:** Semantic HTML form handling diverse inputs:
    * Text Inputs (Title, Course Code)
    * Dropdown Selects (Subject Category)
    * File Uploads (Restricted to `.pdf`, `.doc`, `.docx`)
* **UX Micro-copy:** Clear helper text and placeholders to guide user input.

### 4. ℹ️ Information Architecture (`about.html`, `features.html`)
* **Mission Statement:** Text-heavy sections styled for readability with generous line-height (`1.6`).
* **Value Propositions:** Numbered grid layout highlighting the core benefits (Quality, Community, Free Access).

---

## 🛠️ Technical Implementation

### Core Technologies
* **HTML5:** Utilized semantic tags (`<header>`, `<main>`, `<article>`, `<section>`, `<footer>`) for SEO and accessibility.
* **CSS3:**
    * **Variables (`:root`):** For maintainable theming.
    * **Flexbox:** Used for navigation bars and internal component alignment.
    * **CSS Grid:** Used for the main responsive layouts (`grid-template-columns: repeat(auto-fit, ...)`).
    * **Media Queries:** Breakpoints at `768px` (Tablet) and `480px` (Mobile) to ensure responsiveness.

### Directory Structure
```
NotesFlow/
├── index.html       # Landing Page (Hero & Stats)
├── about.html       # Mission & Story
├── features.html    # Detailed Platform Capabilities
├── browse.html      # Search Interface & Results Grid
├── upload.html      # Note Submission Form
├── contact.html     # Support & Feedback Form
├── style.css        # Global Stylesheet & Variables
├── logo.png         # Project Logo
└── README.md        # Documentation
```
## Screenshots: 

<img width="1884" height="901" alt="image" src="https://github.com/user-attachments/assets/a3541ecf-f09a-41ee-98ff-81f8fea19227" />
<img width="1812" height="863" alt="image" src="https://github.com/user-attachments/assets/b721114f-b3c7-4b6a-8129-14cc165495e1" />
<img width="1877" height="872" alt="image" src="https://github.com/user-attachments/assets/6d101c0a-c546-41d6-88c4-cad31aef3735" />


```Continued...```
## 🏆 Credits

**Development Team:**
* **Muhammad Umer Fareed** 
* **Muhammad Hamza Hassan** 
* **Ahmad Ibraheem** 

**Supervised By:**
* **Mr. Moazzam Ali**

**Course:**
* AICT (Applications of Information & Communication Technologies)

---
<p align="center">
  <i>"Education should be collaborative, not competitive."</i>
</p>
