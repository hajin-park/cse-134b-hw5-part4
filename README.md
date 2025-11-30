# cse-134b-hw5-part4

## Part 4 Enhancements

These updates focused on enhancing the portfolio's pastel/highlighter theme while improving semantic HTML structure and accessibility. I also implemented features missing such as the theme toggle using JavaScript.

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
- Added form validation error and success state styling
- All new styles use the existing CSS custom properties from `variables.css` for design system consistency

**JavaScript Features:**
- Theme toggle button: Floating button that allows users to manually switch between light and dark themes, with localStorage persistence and system preference detection
- Form validation: Client-side validation for the contact form with real-time error feedback on blur, accessible ARIA attributes, and success message display

**Rationale & Improvements:**
These enhancements improve the site by: (1) making content more accessible to screen readers through semantic HTML and ARIA attributes, (2) creating visual hierarchy and polish with the expanded pastel theme, (3) improving user experience with form validation, theme preferences, and focus states, and (4) maintaining a cohesive visual identity across all pages using the design system variables.