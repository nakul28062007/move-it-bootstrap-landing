# moveit-bootstrap-landing

A responsive landing page for a fictional moving company, built as a Bootstrap practice exercise from Angela Yu's Web Development Bootcamp.

## What This Is

A course exercise. Not an original design — the layout and copy follow the bootcamp curriculum. The goal was to get comfortable with Bootstrap's component system and grid.

## What I Practiced

- Bootstrap 5 navbar with collapse, dropdown, and inline search
- Hero section with centered text and a clipped image
- Responsive 3-column feature grid using `row-cols-lg-3`
- Bootstrap carousel with indicators and prev/next controls
- Multi-column footer layout
- Google Fonts integration
- Custom utility class on top of Bootstrap defaults (`.feature-icon`, `.title-text`)

## Structure

```
moveit-bootstrap-landing/
├── index.html
└── assets/
    ├── images/
    │   ├── moving-van.jpg
    │   ├── couple.jpg
    │   ├── dog.jpg
    │   └── family.jpg
    └── icons/
        ├── box-seam.svg
        ├── briefcase.svg
        ├── bus-front.svg
        ├── chat-square-heart.svg
        └── chevron-right.svg
```

## Stack

- HTML5
- Bootstrap 5.3
- Google Fonts (Alex Brush)
- No JavaScript beyond Bootstrap's bundle

## How to Run

Clone the repo and open `index.html` directly in a browser. No build step needed.

```bash
git clone https://github.com/nakul28062007/moveit-bootstrap-landing.git
cd moveit-bootstrap-landing
open index.html
```

## What I'd Do Differently

- Add a working postcode validation with JavaScript before the form submits
- Replace the generic footer placeholder links with actual page sections
- Add a pricing or testimonials section to make the page more complete
