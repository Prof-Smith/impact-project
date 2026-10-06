# Quality Audit

The GitHub Pages shell was reviewed after the requested update.

## Naming

- All visible and metadata references use **Impact Project**.
- The institution name has been removed from HTML, CSS, JavaScript, and repository documentation.

## Brand palette

- Primary green: `#195E47`
- Accent gold: `#FFC72C`
- Supporting dark green, cream, white, and charcoal remain for hierarchy and accessibility.

## Scope boundaries

- No submission form
- No file upload
- No student-data collection
- No AI integration
- No database or external dependency
- No academic approval functionality

## Technical checks

- Seven HTML pages present
- Navigation included once on every page
- Internal HTML links resolve
- CSS and JavaScript assets resolve
- Responsive viewport metadata present
- Skip navigation included
- Main content landmark included
- GitHub Pages instructions preserved in `README.md`

## Corrective color verification

- All legacy blue/navy hex values were removed from the stylesheet.
- The active stylesheet was renamed to `impact-brand-v2.css`.
- Every HTML page references the new stylesheet with a version query string.
- A `.nojekyll` marker was added for direct static publishing.
- The ZIP places deployable files at the archive root to prevent accidental nested-folder publishing.
