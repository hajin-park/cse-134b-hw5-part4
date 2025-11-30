# cse-134b-hw5-part4

## Part 4 Enhancements

This assignment focused on enhancing the portfolio's pastel/highlighter theme while improving semantic HTML structure and accessibility.

### Changes Made

**HTML Improvements:**
- Replaced all `<div>` tags with semantic elements (`<article>`, `<section>`, `<address>`, `<time>`) to improve accessibility and document structure
- Added `<time>` elements with `datetime` attributes for machine-readable dates throughout career and project pages
- Improved form structure using `<p>` elements with appropriate classes instead of generic containers
- Added `rel="noopener noreferrer"` to all external links for security
- Added `placeholder` attributes to form inputs for better user experience

**CSS Enhancements:**
- Extended the pastel/highlighter theme with a yellow highlighter underline effect on all `h2` headings, creating visual consistency with the navbar highlighter animation
- Styled contact page with a responsive grid layout and pastel gradient accent cards
- Created comprehensive form styling with focus states, transitions, and themed buttons
- Added project cards with hover effects, corner gradient accents, and button-style link styling
- Implemented timeline-style experience entries with left borders, gradient backgrounds, and decorative dots
- All new styles use the existing CSS custom properties from `variables.css` for design system consistency

**Rationale & Improvements:**
These enhancements improve the site by: (1) making content more accessible to screen readers through semantic HTML, (2) creating visual hierarchy and polish with the expanded pastel theme, (3) improving user experience with form placeholders and focus states, and (4) maintaining a cohesive visual identity across all pages using the design system variables.