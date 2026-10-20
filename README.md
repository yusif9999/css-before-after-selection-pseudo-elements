# Classic CSS Restaurant UI: Eastern Taste

A responsive, single-page restaurant menu and reservation interface built entirely with pure HTML5 and classic CSS3.

This project serves as a practical implementation of foundational CSS concepts, focusing on classic layout techniques and advanced element targeting without relying on modern layout modules like Flexbox or CSS Grid.

## 🚀 Key Features & Learnings

*   **Classic Layouts:** Fully structured two-column layout utilizing `float: left` and `float: right`, managed with a custom `.container::after` clearfix solution to prevent float collapsing.
*   **Pseudo-Elements (`::before`, `::after`, `::selection`):**
    *   Custom text selection colors matching the restaurant's theme.
    *   Decorative icons and typography enhancements (Drop caps using `::first-letter` and `::first-line`).
    *   Pseudo-element injection for structural spacing and visual dividers.
*   **Interactive Pseudo-Classes:**
    *   Form validation UI changes using `:invalid`.
    *   State management with `:focus`, `:hover`, `:active`, `:disabled`, and `:enabled`.
    *   Adjacent sibling combinators (`+`) to dynamically style labels based on `:checked` checkbox states.
*   **Data Presentation:** Structured tabular data for the restaurant menu using heavily styled HTML `<table>`, `<thead>`, `<tbody>`, and `<tr>`/`<td>` elements.
*   **Absolute Positioning:** Precise placement of custom badges (e.g., "Chef's Choice") within relative table cells.

## 🛠️ Built With

*   **HTML5** - Semantic markup, form validations, and language tags
*   **CSS3** - Custom styling, combinators, nesting hierarchy, and positioning
*   **FontAwesome 6** - Vector iconography
*   **Google Fonts** - Typography (Playfair Display & Roboto)

## 📂 How to Run

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yusif9999/css-before-after-selection-pseudo-elements.git
   ```
2. Navigate to the project folder.
3. Open the `index.html` file in any modern web browser. No local server or build tools are required.
