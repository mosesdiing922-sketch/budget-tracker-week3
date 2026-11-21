# My Budget Tracker

A personal budget and expense tracker built step by step as a web development course project.
This is the **Week 3** version: a full visual redesign using CSS only. No new HTML structure or
functionality was added. The only HTML change is the Google Fonts `<link>` tags in the `<head>`.

## What I built

### Color palette (defined as CSS variables in `:root`)
| Role | Color |
|------|-------|
| Page background | `#eef3ef` (soft sage) |
| Cards | `#ffffff` |
| Primary (headings, buttons, table header) | `#1f5c47` (forest green) |
| Accent (underlines, card top borders, focus ring) | `#e8a33d` (amber) |
| Text | `#22302a` |
| Alternating table rows | `#f1f7f3` |
| Row hover | `#fbecd0` |

Every section uses these same variables, so the whole page stays consistent and the theme can be
changed from one place.

### Typography
- **Merriweather** (serif) for the `h1` and `h2` headings.
- **Inter** (sans-serif) for body text, labels, inputs, buttons and table content.
- Both are loaded from Google Fonts in `index.html` and have fallbacks (`Georgia, serif` and `Arial, sans-serif`).

### Table and form styling
- Table: rounded outer border, padded cells, a green header row with an amber bottom border,
  alternating row colors, a hover color, and the amount column aligned to the right.
- Form: labels in the primary color, inputs and dropdown with matching padding, borders and
  rounded corners, an amber focus ring, and a button that darkens on hover.

### CSS box model
- `box-sizing: border-box` on all elements.
- **Padding** inside every card and in table cells and inputs.
- **Margin** (24px) between cards.
- **Borders** to define each card, with a colored 6px top border on the form, table and video cards.
- **Border radius** (14px on cards, 8px on inputs and buttons) for a softer look.
- The page heading, the Add Expense form and the Expense Table each appear as a separate card.

## Files
- `index.html`: page structure (same as Week 2, plus font links)
- `style.css`: all styling
- `logo.svg`: logo image
- `README.md`: this file

## How to run
Open `index.html` in a web browser. Keep all files in the same folder. An internet connection is
needed to load the fonts and the video.
