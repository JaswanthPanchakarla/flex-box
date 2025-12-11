# 📚 Flexbox Basics: HTML Structure and CSS Layout

This repository contains the files used to demonstrate fundamental web development concepts: creating a semantic **HTML structure** and styling it using modern **CSS Flexbox**.

This work was developed as a key step in learning modern layout techniques, guided by **The Odin Project** and resources like the **Interneting Is Hard** Flexbox tutorial.

---

## 🧱 Structure (HTML)

The `index.html` file provides the full structural scaffolding for the page demonstration. It includes:

* **Menu/Header:** Contains nested `div`s for navigation links, date, logo, and social icons.
* **Photo Grid:** Contains five individual items to test wrapping and ordering.
* **Footer:** Contains three distinct items designed to demonstrate static and flexible sizing.

The HTML is intentionally designed to be clean and minimal, allowing the CSS to control all alignment and positioning.

---

## 🎨 Layout & Styling (CSS Flexbox)

The `style.css` file implements a wide range of advanced layout properties. Key concepts demonstrated include:

| CSS Property / Concept | Purpose Demonstrated |
| :--- | :--- |
| **Containers** | `display: flex;`, `justify-content: center;`, `align-items: center;` | Creating flexible containers and mastering basic horizontal and vertical centering. |
| **Item Spacing** | `justify-content: space-between;` | Efficiently distributing elements across a container's width. |
| **Flow Control** | `flex-wrap: wrap;`, `flex-direction: column;` | Creating multi-row grids and dynamically changing the main axis (row to column). |
| **Sizing & Flexibility** | `flex: 1;`, `flex: initial;`, `width` | Combining flexible (stretching) items with fixed-width (static) elements in the footer. |
| **Individual Control** | `order`, `align-self` | Overriding the container rules to control the visual position of individual items. |
| **Utility** | `margin: auto;` on items | Using auto-margins to push and group links without additional wrapping HTML. |

---

## 💻 How to View

1.  Clone the repository:
    ```bash
    git clone git@github.com:JaswanthPanchakarla/flex-box-basics.git
    ```
2.  Open the main HTML file (`index.html`) directly in your browser.
3.  **Review the Commit History:** The commit messages provide a clear, step-by-step log of the Flexbox rules implemented at each stage of the learning process.
