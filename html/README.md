# Harbor House College Hostel

A responsive, single-page hostel website built with semantic HTML and CSS. The page has no JavaScript dependencies; interactions use browser-native HTML controls and CSS states.

## Files

- `index.html` contains the page structure, navigation, room and facility content, accessible form labels, and footer.
- `style.css` contains the color tokens, layout, responsive breakpoints, animations, hover/focus states, and CSS-only interactions.

## Page flow

1. Sticky navigation links to each main section.
2. Full-height hero introduces Harbor House and links to room options.
3. Intro and facilities explain the community and on-site services.
4. Room cards present room types, images, and indicative monthly prices.
5. House rules use native `<details>` and `<summary>` elements. The open/closed state and content reveal are styled with CSS, so each item works with a keyboard and without a script.
6. Contact details and the enquiry form lead into the footer links.

## Responsive design

The CSS starts with the wide layout, then adapts at 1020px, 760px, and 520px. Facility and room grids reduce their column count as the viewport narrows. The layout is tested to avoid horizontal scrolling on phone-sized screens.

## Accessibility and motion

The page includes a skip link, semantic landmarks, descriptive image alt text, explicit form labels, visible keyboard focus, and reduced-motion handling. The Poppins typeface and room photography are loaded from Google Fonts and Unsplash, so those assets require an internet connection.

## Run locally
Open `index.html` in a browser. No build step or package installation is required. The contact form uses a `mailto:` action and opens the visitor's configured email application; a real hosted form endpoint would be needed to submit enquiries directly to a server.