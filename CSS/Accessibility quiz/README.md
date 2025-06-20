📘 Accessibility Quiz – HTML/CSS Project
This project is a practice quiz webpage built as part of the freeCodeCamp Accessibility Certification Path. It demonstrates fundamental skills in semantic HTML, accessible form design, Flexbox layout, and responsive styling.

🔧 Files Included
index.html – Main HTML structure of the quiz

styles.css – External stylesheet for visual design and layout

🗂️ index.html Overview
This file contains the semantic structure for the quiz webpage:

Key Sections:

<header>: Contains the logo, main heading, and navigation menu

<main>: Includes a form broken into three fieldset-driven sections:

Student Info

HTML Questions

CSS Questions

<footer>: Displays site credit

Accessibility Features:

Uses ARIA attributes like aria-labelledby and role="region" for assistive technologies

Semantic grouping with <fieldset> and <legend>

Properly associated <label> and input using for and id

Descriptive value attributes on radio inputs

Logical heading hierarchy (h1, h2)

Anchor links for keyboard-friendly navigation

🎨 styles.css Overview
This file defines the visual and layout styling for the webpage.

Highlights:

Font & Colors: Uses accessible fonts and ensures color contrast ≥ 7:1

Layout:

Flexbox used in <header> and <footer> for alignment

Responsive widths (80% with max-width) to optimize reading space

Forms:

Labels and inputs aligned with inline-block and width controls

Minimal padding for focus and spacing

Default fieldset and list styles removed for a clean look

Navigation:

Styled to resemble buttons, with text-decoration: none, cursor pointer, and hover feedback

Motion & UX:
scroll-behavior: smooth added inside:

css
@media (prefers-reduced-motion: no-preference) {
  * {
    scroll-behavior: smooth;
  }
}
This respects user system preferences and enhances navigation experience.

✅ Skills Demonstrated
Semantic HTML & accessible forms

CSS Flexbox layout

Responsive design techniques

Visual accessibility via color contrast & sizing

Respect for reduced motion preferences