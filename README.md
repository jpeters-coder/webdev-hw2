# webdev-hw2

Web Development Homework 2: Styling Your Page

## Homework 3 — Responsive Layout

The Homework 2 page is reorganized with Flexbox and Grid. The navy (`#0f172a`) and amber (`#f59e0b`) palette and the original copy are unchanged.

- The header is a Flexbox row: the title and navigation sit side by side when there is room, and wrap onto separate lines on a narrow screen.
- About and Current Projects form a grid that is one column by default and two columns from `min-width: 768px`.
- The project list is a card grid: one column by default, two columns at `768px`, and three columns at `min-width: 1200px`.
- `box-sizing: border-box`, the viewport meta tag, and `max-width: 100%` on images keep the layout usable at 320px, 768px, and 1200px with no horizontal scrolling.
