# Portfolio Website – Capstone Project

## Overview

This project is a fully functional, multi-page portfolio website developed as part of a debugging and enhancement capstone. The original codebase was approximately 70% complete but contained multiple structural, semantic, accessibility, and styling issues. The goal of this project was to transform the incomplete starter code into a professional, accessible, and well-structured website using only HTML and CSS.

The final website consists of four pages: Home, About, Projects, and Contact. It demonstrates proper semantic HTML usage, responsive layout techniques, improved accessibility, and structured CSS styling.

---

## Issues Found

During the initial audit, several major issues were identified:

* Missing semantic HTML structure (overuse of `<div>` elements)
* Missing metadata (lang, charset, viewport)
* No navigation system across pages
* Images missing alt text and inconsistent file paths
* Missing required table in About page
* Incomplete form in Contact page (no labels, insufficient input types, no validation)
* Poor accessibility (no labels, weak structure)
* Incomplete CSS (no navigation styling, no table/form styling)
* Insufficient selector variety and no pseudo-classes
* Weak layout and alignment across pages
* Poor typography and inconsistent colour usage

---

## Fixes Implemented

To address the issues identified, the following improvements were made:

* Replaced non-semantic elements with proper HTML5 semantic tags (`header`, `nav`, `main`, `section`, `article`, `footer`)
* Added required metadata (lang attribute, charset, viewport)
* Implemented a consistent navigation menu across all pages (16 working links)
* Added descriptive alt text to all images and corrected image paths
* Created a structured data table on the About page
* Rebuilt the Contact form with:

  * 5+ input types (text, tel, email, select, textarea, radio, checkbox)
  * Proper label associations
  * HTML5 validation attributes (required, pattern, minlength)
* Improved accessibility through proper structure and form labeling
* Developed a complete CSS system including:

  * 5+ selector types (element, class, ID, descendant, pseudo-class)
  * Pseudo-classes (`:hover`, `:focus`)
  * Box model usage (margin, padding, border)
  * Flexbox and Grid layout systems
* Styled navigation, table, and form components
* Implemented a consistent colour scheme and improved typography
* Added responsive design using media queries

---

## HTML Structure

The website follows a consistent semantic structure across all pages:

* `<header>`: Contains site title and navigation menu
* `<nav>`: Provides internal links across all pages
* `<main>`: Holds primary page content
* `<section>`: Groups related content
* `<article>`: Used for individual project entries
* `<footer>`: Contains contact information and copyright

This structure improves readability, maintainability, and accessibility.

---

## CSS Styling Approach

The CSS was organized into logical sections and built using a structured approach:

* Global styles and CSS variables for consistent theming
* Layout using Flexbox and CSS Grid
* Navigation styling with hover effects
* Typography hierarchy (headings, paragraphs, spacing)
* Form styling with clear visual grouping and focus states
* Table styling including borders, spacing, and alternating rows
* Responsive design using media queries

The styling ensures visual consistency, usability, and accessibility across all pages.

---

## Accessibility Improvements

* Added descriptive alt text to all images
* Implemented proper label associations for all form inputs
* Used semantic HTML to improve screen reader navigation
* Ensured logical document structure
* Added validation attributes for better user input handling
* Improved colour contrast for readability

---

## How to View the Website

1. Download or clone the repository
2. Open the project folder
3. Open `index.html` in a web browser
4. Use the navigation menu to access all pages

No additional setup or dependencies are required.

---

## Screenshots

The project includes screenshots demonstrating:

* Home page
* About page
* Projects page
* Contact page
* Completed form
* Styled table
* Navigation menu with hover effects

Screenshots are located in the `/screenshots` folder.

---

## Reflection

One of the main challenges in this project was identifying and systematically fixing all structural and accessibility issues across multiple files. Ensuring consistency between pages while meeting strict requirements required careful planning and attention to detail.

Another challenge was transforming incomplete CSS into a fully structured styling system that meets both visual and technical requirements. This involved learning how to properly apply layout techniques, improve typography, and maintain consistency across components.

Through this process, I developed a deeper understanding of semantic HTML, accessibility principles, CSS architecture, and debugging workflows. The project reinforced the importance of structured planning, validation, and incremental improvements when working on real-world codebases.

---

## Repository Structure

```
portfolio-website/

├── index.html
├── about.html
├── projects.html
├── contact.html

├── css/
│   └── styles.css

├── images/

├── design/
│   ├── wireframe.pdf
│   └── issues-identified.pdf

├── screenshots/

└── README.md
```