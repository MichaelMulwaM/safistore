# SafiStore Project

Hi! Welcome to my SafiStore project. I am a junior web development student, and this is my portfolio project built with HTML5 and CSS3.

---

## Project Overview

SafiStore is a minimalist, eco-friendly e-commerce website designed to showcase sustainable, locally sourced products in Kenya. The main goal of this project was to build a multi-page web application focusing on clean code, green branding, and practical shopping layouts, including:

* Multi-Page Architecture: Connecting Home, Products, About Us, Contact, and Login pages seamlessly.
* Grid Section: Featuring background product imagery with absolute text positioning and responsive overlays.
* Product Catalog: Structured across three key categories (Reusable Shopping, Kitchen & Dining, and Personal Care), complete with KES pricing and discounted strike-through tags (<del>).
* Minimalist UI Components: Includes a side-by-side login page, a structured contact page, and a clean Flexbox footer with social media icons.

---

## Key Technical Features

* CSS Flexbox & Grid Layouts:
  * Flexbox: Used in the navigation header, footer, alignment controls, and form structures.
  * CSS Grid: Applied across the product catalog and spotlight sections to ensure fluid responsiveness.
* Background Image Positioning: Utilized background-size: cover combined with absolute positioning to overlay text cleanly over product photography.
* Semantic HTML Markup: Built using modern structural elements (<header>, <nav>, <section>, <main>, <footer>).
* Typography & Units: Maintained consistent scaling using rem units and styled with a signature green theme.

---

## File & Folder Structure

```text
/safi-store
├── index.html        # Main landing page & spotlight section
├── products.html     # Product catalog page
├── about.html        # About Us page
├── contact.html      # Contact form and details page
├── login.html        # Authentication page
├── styles.css        # Custom CSS stylesheet
└── /images           # Assets folder for product and banner images

How to Run the Project
• Download or clone this repository to your local machine.

• Ensure all HTML files, styles.css, and the images/ directory are in the same folder root.

• Open index.html in any modern web browser (Chrome, Firefox, Safari, Edge) to start exploring the site.

Concepts Learned This Week
• Structuring multi-page websites and maintaining consistent navigation across views.

• Applying background image properties (background-size: cover, background-position: center) for modern e-commerce card designs.

• Designing functional form layouts for user registration and contact submissions.

• Using semantic elements like  to clearly indicate original sale prices.

Challenges & Future Enhancements
• Spotlight Text Overlay: Getting the text and buttons to sit right on top of the background images without messing up responsiveness on smaller screens took quite a bit of trial and error with absolute positioning.

• Forms Don't Submit Yet: The login and contact forms are purely frontend templates and do not connect to a backend server to process submissions or messages.

• Cart Functionality is Static: Clicking "Add to Cart" or interacting with cart buttons doesn't dynamically update item quantities or totals yet.

Created as part of Web Development Coursework by Michael Mulwa — 2026.