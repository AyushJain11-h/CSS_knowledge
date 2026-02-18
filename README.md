CSS Cheat Sheet Repository 🎨

Welcome to the CSS Cheat Sheet Repository – a complete reference for learning and mastering CSS (Cascading Style Sheets). This repository is designed to help developers, students, and web enthusiasts quickly access CSS concepts, properties, and techniques without searching through multiple tutorials.

📌 What is CSS?

CSS (Cascading Style Sheets) is a language used to style HTML elements. It allows you to control the layout, colors, fonts, spacing, animations, and responsiveness of your web pages. With CSS, you can turn simple HTML structures into beautiful and interactive websites.

📝 Contents of this Repository

This cheat sheet covers all essential aspects of CSS, organized for easy learning and reference:

1. CSS Syntax

Basic syntax:

selector {
    property: value;
}


Example:

p {
    color: blue;
    font-size: 16px;
}

2. Selectors

Element Selector: p { ... }

ID Selector: #header { ... }

Class Selector: .menu { ... }

Universal Selector: * { ... }

Attribute Selector: [type="text"] { ... }

Pseudo-classes: :hover, :focus, :nth-child()

Pseudo-elements: ::before, ::after

3. Colors & Backgrounds

color, background-color, background-image

Gradient backgrounds: linear-gradient(), radial-gradient()

Transparency: opacity and rgba()

4. Text & Fonts

font-family, font-size, font-weight, font-style

text-align, text-decoration, text-transform, letter-spacing, line-height

5. Box Model

Elements are boxes: content → padding → border → margin

Properties: width, height, padding, margin, border, box-sizing

6. Display & Positioning

display: block, inline, inline-block, none, flex, grid

position: static, relative, absolute, fixed, sticky

top, right, bottom, left, z-index

7. Flexbox

Container properties: display: flex, flex-direction, justify-content, align-items, flex-wrap

Item properties: flex, order, align-self

8. Grid

Container properties: display: grid, grid-template-columns, grid-template-rows, gap

Item properties: grid-column, grid-row, justify-self, align-self

9. Transitions & Animations

Smooth changes: transition: property duration easing;

Keyframes animations:

@keyframes example {
    0% { transform: scale(1); }
    100% { transform: scale(1.5); }
}

10. Responsive Design

Media queries:

@media (max-width: 768px) {
    body { font-size: 14px; }
}


Mobile-first design principles

Relative units: %, em, rem, vh, vw

11. CSS Best Practices

Use semantic class names

Avoid inline styles

Keep CSS organized with comments

Use CSS variables for reusable values:

:root {
    --primary-color: #3498db;
}
button {
    background-color: var(--primary-color);
}

🚀 Why Use This Cheat Sheet?

Quick Reference – No need to search multiple websites.

Well-Structured – Topics are organized for learning and quick lookup.

Examples & Snippets – Ready-to-use CSS for your projects.

Beginner-Friendly – Explains CSS concepts in simple terms.

🌟 Contributing

Contributions are welcome! If you want to add new tips, examples, or advanced CSS techniques, feel free to open a pull request.

📂 Folder Structure
css-cheatsheet/
│
├─ basics.md        # CSS syntax, selectors, properties
├─ layout.md        # Flexbox, Grid, Box model
├─ effects.md       # Transitions, animations, hover effects
├─ responsive.md    # Media queries, responsive tips
└─ README.md        # This file
