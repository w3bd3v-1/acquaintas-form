# Acquaintas Global — website details form

A single-page intake form used to collect the information needed before the
Acquaintas Global website goes live: contact details, company registration
numbers, team confirmations, and case-study material.

Nothing is submitted anywhere. Answers are held in the visitor's own browser
via `localStorage`, and leave it only when the visitor presses **Copy all
answers** or **Download as a file** and sends the result themselves. There is
no backend, no analytics, no cookies, and no third-party request other than
Google Fonts.

The page is marked `noindex, nofollow` and `robots.txt` disallows crawling, so
it should not appear in search results. It is nonetheless served from a public
URL — treat the link as unlisted, not private.

Single file: `index.html`. Edit and push; GitHub Pages redeploys automatically.
