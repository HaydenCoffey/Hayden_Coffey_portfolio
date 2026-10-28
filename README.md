# Hayden Coffey — Personal Portfolio

A three-page personal portfolio with a styled Home page and a separate CSS file.

## Site Plan / Wireframe

![Wireframe for the Home, Projects/Work, and About/Contact pages](assets/wireframe.png)

The wireframe preserves the original planning stage. The Home page now links to `styles.css`; Projects/Work and About/Contact retain their original HTML skeletons.

### Original Planned Color Palette

| Use | Color | Hex |
| --- | --- | --- |
| Header, footer, headings | Navy | #16243A |
| Links and accents | Teal | #087F8C |
| Page background | Off-white | #F6F7F9 |
| Body text | Charcoal | #243247 |

### Planned Fonts

- Headings: Georgia, with a serif fallback.
- Body and navigation: Arial, with a sans-serif fallback.
- The styled Home page uses Georgia headings and Arial body text. No font downloads are needed.

## CSS Assignment

The Home page links to `styles.css` in its `<head>`. It uses a complementary blue (`#173F73`) and orange (`#F4A340`) scheme with neutral backgrounds.

- Type selector: `p` (also `body`, `section`, and heading elements).
- Class selector: `.project-card` (also `.button`).
- ID selector: `#welcome`.
- Box model: `section`, `#welcome`, and `.project-card` each explicitly set margin, padding, and border.
- Layout includes styled navigation, readable typography, highlighted content panels, and a footer.

## Responsive Layout Assignment

The Home page uses CSS Grid for the Featured Work and What I Bring sections, plus Flexbox navigation.

| Viewport width | Content layout | Navigation |
| --- | --- | --- |
| 320px | One stacked column | Vertical links |
| 768px | Two equal columns | Horizontal links |
| 1200px | Two columns with a 3:2 ratio | Horizontal links |

Explicit media queries at 700px and 1000px visibly change the layout. Flexible tracks, wrapping text, and border-box sizing let the content fit narrow screens without hiding overflow.

### Verify in Your Browser

1. Open `index.html` from the extracted folder in Chrome or Edge.
2. Press F12, then Ctrl+Shift+M to open device emulation.
3. Choose Responsive and set the width to 320px, then 768px, then 1200px.
4. Confirm the sections stack at 320px and appear side by side at 768px and 1200px. Navigation also changes from vertical to horizontal.
5. Scroll through the page at each width and confirm all text and links remain visible, with no horizontal scrolling or overlapping content.

Source checks confirmed the stylesheet link, Grid container, two direct section children, media queries, and working relative page links. Automated browser rendering was unavailable in the build environment; perform the viewport checks above before submitting.

## Pages

| File | Purpose |
| --- | --- |
| [index.html](index.html) | Styled Home page with introduction, featured project, and strengths |
| [styles.css](styles.css) | Separate stylesheet for the Home page |
| [projects.html](projects.html) | Portfolio project, wireframe, and planned work samples |
| [about.html](about.html) | Background, interests, goals, and contact placeholders |

Each page includes the same navigation with relative links, one h1, h2 sections, h3 subsections, and semantic header, nav, main, section, and footer elements. Placeholder work samples and contact details are labeled clearly.

## Open the Site

Download the repository and open `index.html` in a browser. No installation or build tools are required.

## Upload and Submit

1. Create a GitHub repository named `personal-portfolio` (or use your assigned repository).
2. Select **Add file → Upload files** inside the repository.
3. Upload the contents of this folder, including the `assets` folder. Extract the ZIP first; uploading only the ZIP will not make the HTML files and wireframe visible individually.
4. Commit the files and confirm the root contains `index.html`, `projects.html`, `about.html`, `styles.css`, and this README, with `assets/wireframe.png` inside `assets`.
5. Submit the repository URL from your browser's address bar. A GitHub Pages deployment is not required for this assignment.
