# Responsive Sections Layout with CSS

This project demonstrates a simple, responsive webpage layout using HTML and CSS.  
It focuses on arranging multiple `<section>` elements horizontally without using advanced CSS techniques like Flexbox or Grid, making it beginner-friendly.

---

## Features

- Responsive body width based on viewport (`80vw`)
- Minimum height calculated to account for padding using `calc()`
- Horizontal layout of `<section>` elements using `inline-block`
- Centered header, footer, and sections for neat presentation
- Simple CSS that is easy to understand and modify

---

## Installation

1. Clone or download this repository.

## Usage

- Open the `index.html` file in your preferred browser to view the layout.
- Modify the `<section>` content inside `index.html` to add your own sections.
- Customize styles in `style.css` to change widths, colors, padding, etc.
- Great starter project for learning CSS layout basics before moving to Flexbox or Grid.

## Code Highlights

- `body` width is set to `80vw` to be relative to the viewport width.
- `min-height` uses `calc(100vh - 100px)` to subtract vertical padding from viewport height.
- Sections use `display: inline-block` and fixed widths to sit side-by-side horizontally.
- Parent container uses `text-align: center` to center the inline-block sections.

