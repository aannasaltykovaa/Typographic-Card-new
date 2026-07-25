I used Gemini for the first draft, then used ChatGPT to review and improve the HTML, CSS, accessibility, design, and testing documentation.

Features

Article image, badge, headline, description, and article link

Light and dark themes

CSS custom properties on :root

oklch() color tokens

Fluid typography with clamp()

text-box: trim-both cap alphabetic on the badge and article link

Relative CSS units and no !important

Responsive layout

Keyboard focus styles

Saved theme preference

Reduced-motion support

Embedded SVG image so no separate image file is required

How to Run

Open index.html in a browser. 

Article

The card links to “In Focus: High Press” from Coaches’ Voice:

https://learning.coachesvoice.com/cv/in-focus-high-press/

AI Prompt

Create a responsive article card with an image, category badge, headline, short description, and Read Article link.

Use semantic HTML, low-specificity class selectors, CSS custom properties on :root, oklch() colors, a light/dark theme, fluid clamp() typography, relative units, and text-box: trim-both cap alphabetic on the badge and link. Do not use px or !important.

Make the page responsive, accessible, and visually polished.

Changes Made During the Audit

Replaced the nonfunctional button with a real article link

Improved light and dark color contrast

Added keyboard focus styles

Added aria-pressed to the theme toggle

Saved the selected theme with localStorage

Added reduced-motion support

Embedded the image directly in the HTML to prevent broken file paths

Added fallback padding for browsers that do not support text-box

