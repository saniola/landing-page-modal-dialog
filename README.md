# Landing Page Modal Dialog

A multi-section landing page for a design/development studio, with a portfolio subpage and a toggleable modal dialog.

## Features

- Hero, services (with icon sprite), portfolio, team, and customers sections
- Portfolio subpage (`portfolio.html`) with project filtering markup
- Modal dialog toggled via `js/modal.js`, opened from the hero "Order Service" button

## Technology

- Semantic HTML
- CSS (flexbox, custom properties)
- Vanilla JavaScript for modal interactions

## Project structure

```
index.html        Main landing page
portfolio.html     Portfolio subpage
css/
  normalize.css    CSS reset
  styles.css       Site styles
js/
  modal.js         Modal open/close logic
images/            Site images and icon sprite
```

## Running

Open `index.html` directly in a browser, or serve the directory with any static file server, e.g.:

```
npx serve .
```
