# Azure Isles — Travel Brochure

A responsive travel brochure for a fictional island destination, built with semantic HTML and hand-written CSS (no frameworks).

**Live demo:** https://mberry-dev.github.io/travel-brochure/

![Desktop view](TravelBrochure/Screen%20Shots/Large%20Screens%20(desktop).png)

## Features

- **Five themed photo galleries** (Scenic Views, Couples, Explorer, Relax & Spa, Family) built with CSS Grid, with hover zoom and full-size images on click
- **Three responsive layouts** with breakpoints at 1024px and 768px
  - Desktop: four-across galleries; three-photo galleries use a wide middle photo and a full-width banner
  - Tablet: three-across galleries with a full-width fourth photo; two-across plus banner for three-photo galleries
  - Phone: single-column galleries and a stacked navigation bar
- **Packages table** that turns into labeled cards on screens under 600px
- **Inquiry form** with built-in browser validation and an on-page confirmation message
- **Accessibility:** descriptive alt text on every photo, labeled form fields, a live region for the form confirmation, and safe new-tab links
- **Theming** through CSS custom properties for colors and spacing

## Screenshots

| Desktop | Tablet | Phone |
| --- | --- | --- |
| ![Desktop](TravelBrochure/Screen%20Shots/Large%20Screens%20(desktop).png) | ![Tablet](TravelBrochure/Screen%20Shots/Medium%20Screens%20(tablets).png) | ![Phone](TravelBrochure/Screen%20Shots/Small%20Screens%20(mobile).png) |

## Built With

- HTML5
- CSS3 (Grid, Flexbox, custom properties, media queries)
- A small amount of vanilla JavaScript (form confirmation, footer year)

## Project Structure

```
travel-brochure/
├── .github/workflows/pages.yml   # Deploys TravelBrochure/ to GitHub Pages
└── TravelBrochure/
    ├── index.html
    ├── style.css
    ├── images/                   # Gallery photos
    └── Screen Shots/             # Desktop, tablet and phone screenshots
```

## Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/mberry-dev/travel-brochure.git
   ```
2. Open `TravelBrochure/index.html` in your browser.

## Deployment

Every push to `main` deploys the `TravelBrochure/` folder to GitHub Pages through the workflow in `.github/workflows/pages.yml`.

## Notes

The inquiry form is a front-end demo: it validates input and shows a confirmation, but does not send data anywhere.