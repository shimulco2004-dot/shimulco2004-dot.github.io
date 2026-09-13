# Shimul Miah portfolio

A static GitHub Pages portfolio. No build step or package installation is required.

## Files

- index.html: all content, project entries and contact placeholders.
- assets/css/style.css: responsive layout, design tokens and artwork placeholders.
- assets/js/main.js: optional, reduced-motion-aware entry animation.
- .nojekyll: preserves plain static Pages deployment.

## Replace concept projects

Find the six article elements with IDs beginning with project- in index.html. Each contains a title, category, description and artwork. Replace the artwork div with the commented image example. Create assets/images/ and add compressed WebP or AVIF artwork with accurate alternative text and intrinsic width/height. Use the actual image aspect ratio in CSS where needed.

Each article includes commented examples for a confirmed year and an optional case-study link. Leave the link out when there is no destination. Duplicate an article to add work; use the wide class for a featured full-width entry. Replace the concept label only when the entry describes real work. Project descriptions currently explain placeholders, not completed client commissions.

## Contact details required

Search for CONTACT DETAILS in index.html. Replace the non-interactive coming-soon labels with real email, LinkedIn, Behance and WhatsApp links. Do not publish example contact addresses. Confirm project years, imagery and destinations before replacing their placeholders.

## Deployment

Keep the root index.html and .nojekyll. Publish this repository root using the existing GitHub Pages configuration. CSS and JS use relative URLs. No framework, build pipeline or server is needed.

## Design and accessibility

The original page sections and six concept identities are retained. Solid headings, readable descriptions, a consistent spacing scale and responsive grids replace cramped viewport typography. The loading screen, perpetual marquees, fixed noise overlay and blur effects were removed. The page has one H1, section headings, a skip link, visible keyboard focus, native anchor navigation and meaningful artwork labels. Core content works without JavaScript. Motion is disabled under prefers-reduced-motion.

Google Fonts remains the only external asset dependency; system font fallbacks are provided. Core Web Vitals field scores require deployed traffic and are not claimed here.
