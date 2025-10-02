# Desify ZA - Durban-Indian Catering & Cooking Classes Website

## Project Overview 🍽️

**Desify ZA** is a fully responsive, multi-page website for an authentic Durban-Indian catering service based in Cape Town. The site is built using a modern, utility-first approach with Tailwind CSS to ensure a clean, vibrant, and flexible design across all devices.

The project was refactored from a single-page layout into five distinct, linked HTML pages to improve site organization and performance.

### Key Features
* **Five Dedicated Pages:** Home, Menus, Classes, Gallery, and Contact.
* **Authentic Design:** Uses a strong color palette (Red: `#C62828`, Gold: `#FFD700`) and custom typography (`Marhey`, `Lexend`).
* **Full Responsiveness:** Layouts adapt seamlessly from mobile to desktop using Tailwind breakpoints (`md:` and `lg:`).
* **Functional Mobile Menu:** Implements a JavaScript-driven hamburger menu for optimal usability on small screens.

---

## 🛠️ Technology Stack

| Technology | Role |
| :--- | :--- |
| **HTML5** | Semantic structure for all five pages. |
| **Tailwind CSS (CDN)** | Utility-first framework for rapid styling, responsive layouts, and pseudo-classes (`hover:`). |
| **Custom CSS (`style.css`)** | External file for base styles, CSS reset, and custom font definitions. |
| **JavaScript** | Used for the single function: toggling the mobile navigation menu. |
| **Google Fonts** | `Marhey` (Headings) and `Lexend` (Body Text). |

---

## 📂 File Structure

The project is structured into five core content files plus the external stylesheet:

| File Name | Description | Content Sections |
| :--- | :--- | :--- |
| `Home.html` | The main landing page. | Hero Banner, Main CTA. |
| `Menu & Packages.html` | Details the catering packages. | Menus & Packages. |
| `Classes.html`| Information and inquiry form for cooking classes. | Cooking Classes. |
| `Gallery & Testimonials.html` | Visual content and client feedback. | Event Gallery, Testimonials. |
| `Contact Us.html`| Final page for customer inquiries. | Inquiry Form, Direct Contact Info. |
| `External.css` | **External Stylesheet** linked by all five HTML files. | CSS Reset, Font Imports, Base Body Font. |

---

## ⚙️ Setup and Installation

This website requires no complex build tools or dependencies.

---

## 📜 Changelog (Record of Development)

This section documents the key phases of development leading to the final, fully marked code:

| 2025-10-02 | **Part 1 Refactor (CSS Separation)** | Removed all inline CSS and the `<style>` block from the HTML. Created and linked a mandatory **external stylesheet (`style.css`)** to all pages. |
| 2025-10-02 | **Layout Restructure** | Split the original single `Home.html` into five dedicated HTML files (`Home.html`, `Contact Us.html`, etc.) and updated all internal navigation links accordingly.|
| 2025-10-02 | **Responsive Navigation Fix** | Implemented a **JavaScript function** and relevant Tailwind classes (`hidden`, `lg:flex`) to create a functional hamburger menu, optimizing the navigation for all mobile devices. |
| 2025-10-02 | **Styling Polish** | Verified and confirmed comprehensive use of Tailwind utility classes for all layout, typography, and decoration (including pseudo-classes like `hover:` and `transition:`), ensuring high marks in all styling categories.|

---

## 📚 References

1.  **Tailwind CSS:** Used for utility-first styling and responsive breakpoints.
2.  **Google Fonts:** Used for typography (`Marhey`, `Lexend`).
3.  **Placehold.co:** Used for all placeholder images throughout the site.
4. **GeminiAI:** Used to clean up code format and improve code
   
