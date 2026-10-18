# Enterslice — Finance, Compliance & Licensing

A responsive, single-page website concept for **Enterslice**, presenting its finance, regulatory compliance, licensing and advisory services for businesses in India and across borders. This project was created as a UI/UX assignment and is implemented as a self-contained front end.

> **Note:** The activity dashboard uses illustrative sample data only. It does not represent live Enterslice metrics or connect to a backend.

## What’s in the site

- **Landing hero and navigation** — introductory message, primary navigation, and meeting links.
- **Regulatory overview** — a visual introduction to the regulatory landscape and an interactive activity dashboard. Switch between 7-, 30- and 90-day views, inspect the chart, and focus its Regulatory, Finance or Advisory breakdown. The chart can be explored with pointer or keyboard controls.
- **Service practice explorer** — interactive details for six practices: fintech licensing, capital markets, Virtual CFO, audit and assurance, tax and valuation, and global services including GIFT City.
- **How Enterslice works** — differentiators and a four-stage engagement journey: consult, plan, execute and sustain.
- **Global services and insights** — cross-border perspective and links to external articles.
- **FAQ, meeting call to action and footer** — common questions, a link to schedule a meeting, and service, company and legal links.

The page also includes a collapsible navigation menu on smaller screens, a light/dark theme toggle (dark preference is saved in browser `localStorage`), scroll-reveal effects, and an automatically updated footer year.

## Technology

- HTML5 for page structure and accessible controls
- CSS embedded in `index.html` for layout, responsive styling, themes and animation
- Vanilla JavaScript embedded in `index.html` for interactions
- Google Fonts (`DM Sans` and `Fraunces`) loaded externally

There is no package manager, framework, build step, or server-side component required to view the page. An internet connection is needed for the externally hosted fonts and external Enterslice links.

## Run locally

### Open directly

Open `index.html` in a modern browser.

### Serve over HTTP

From the project directory, run:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000). You can also use the VS Code Live Server extension.

## Publish with GitHub Pages

1. Open this repository’s **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose the `main` branch and the `/ (root)` folder, then save.
4. Once the deployment completes, open the Pages URL shown in Settings.

GitHub Pages availability for a private repository depends on your GitHub plan and Pages settings. If the option is unavailable, use a public repository or another static hosting provider.

## Project structure

```text
.
├── index.html   # Complete website: markup, styles and scripts
└── README.md    # Project overview and usage instructions
```

## Customization notes

- Edit the page content, styles, service descriptions, chart sample data and links directly in `index.html`.
- Update the contact and scheduling destinations before using the page for a real organization.
- Replace the illustrative dashboard data with approved, clearly sourced data if the page is adapted beyond a visual prototype.
- To avoid external font requests, replace the Google Fonts import with locally hosted fonts or system font stacks.

## Accessibility

The page includes semantic sections and headings, a skip-to-content link, accessible labels and state for interactive controls, keyboard-operable tabs and chart controls, and reduced-motion-aware reveal effects. Please test changes with keyboard navigation and assistive technologies when adapting the site.
