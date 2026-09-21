# Refit AI

Website for Refit AI, run by Paul Hendrie. Refit AI sets up AI tools for UK small businesses of up to five people, and trains them on their own work: two assistants, a prompt library and templates, three training sessions, a printed playbook and a four-week check-in. Fixed fee, and the client owns everything from day one.

## The site

`index.html` is the site: a single self-contained HTML page with no build step, responsive down to phone width. Fonts (Archivo and IBM Plex Mono) load from Google Fonts. `logo.svg` is the mark, also used as the favicon and inline in the page.

The design is the "Precision" direction: pure black, white type, a visible grid frame, and each section laid out as a table. No eyebrow labels above headings.

Page order: hero, client quote, what I refit, the first refit (case study), what you get, how it works, call to action, independence, pricing, questions, about, contact.

## Placeholders to fill

All in square brackets in `index.html`:

- `[CLIENT QUOTE: …]`, `[Name], [Studio], [Town]` in the quote block
- `[X] hours a week back` in the case study
- `[£X,XXX]` and `[£XXX]` on the three pricing tiers, and `[£XX]` for the monthly subscription
- `[PHOTO OF PAUL]` in About
- `[CALENDAR LINK]` for the booking button and `[YOUR EMAIL]` (also the two `mailto:` links) in Contact
- `[LINKEDIN URL]` in the footer
- `[SITE URL]` in the canonical link, Open Graph tags and structured data, plus an `og.png` share image

## Earlier directions

`mockups/` keeps the two directions that were not chosen (Option A, Editorial and Option C, Monolith) for reference. Open `mockups/index.html` to compare them with the site.
