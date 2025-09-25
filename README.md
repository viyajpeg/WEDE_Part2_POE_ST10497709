# WEDE_Part2_POE_ST10497709 

Desify ZA - Authentic Durban-Indian Catering Website
This repository contains the code for the Desify ZA website, specializing in Durban-Indian cuisine catering and cooking classes in Cape Town.

🚀 Project Overview
The website serves as a portfolio and contact point for Desify ZA, featuring sections for Home, Menus & Packages, Cooking Classes, Gallery, and Contact.

Key Sections

Home: Hero banner promoting "Authentic Durban-Indian Catering".


Menus: Features Buffet, Custom, and Mini Packages.




Classes: Includes information and a booking inquiry form for beginner-friendly cooking classes.


Contact: Contains an inquiry form and direct contact details (phone, email, address).

🛠️ Technology Used
Technology	Role
HTML5	Structure and Content
Tailwind CSS	Styling, Layout (Flexbox & Grid), and Responsive Design
Custom CSS (style.css)	Base styles, CSS Reset, and Font Imports
Google Fonts		
Lexend (Body) and Marhey (Headings) 


Export to Sheets
🎨 Styling and Responsive Design (Part 2 Requirements)
Styling and responsiveness are handled using a combination of an external stylesheet and Tailwind CSS utility classes.

1. External Stylesheet (style.css)
CSS Reset: A basic reset is applied to ensure consistent styling across different browsers.


Font Import: Imports the custom fonts (Marhey and Lexend).


Base Styles: Sets the default font-family for the body element to 'Lexend', sans-serif.

2. Layout Structure & Responsiveness
The layout is mobile-first and uses Tailwind utility classes for structure:


Layout: Uses flex for navigation and the Cooking Classes section , and 



grid for the Menus and Gallery sections.


Breakpoints: Media queries are implemented using Tailwind prefixes:

Mobile (Default): Single column layouts (e.g., in the Contact section).


Tablet (md): Layouts transition to 2 columns (e.g., Testimonials and Menus ).



Desktop (lg): Layouts transition to 3 columns or side-by-side elements (e.g., Menus and Contact form/details ).


3. Visual & Interactive Styles

Color Scheme: Uses #C62828 (Red) as the main brand color, #FFB74D (Orange) for accents, and #FFD700 (Gold) for hover effects.



Interactive Elements: Pseudo-classes are applied via Tailwind for transitions and hovers, such as hover:text-[#FFD700] on navigation links and 

hover:scale-105 transition-transform on content cards.

 References
Google Fonts: 'Marhey' and 'Lexend' (https://fonts.googleapis.com/css2?family=Marhey:wght@300..700&family=Lexend:wght@100..900&display=swap).

Tailwind CSS Documentation (For utility class usage and responsive breakpoints).
