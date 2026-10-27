# Koos roundtable form

A branded front end for the Koos & Co Roundtable Google Form ("Which AI challenges are you facing?"), published with GitHub Pages.

It stores nothing. Answers are posted straight to the Google Form, so they land in the form's responses and its linked Google Sheet as normal.

- Preview without sending anything: add `?preview` to the URL.
- If a question changes in the Google Form, update the `FORM` block at the top of the script in `index.html` (each question's `entry` id), then test with one real submission.

Source and background: `04_experiments/google-form-frontend/` in `koos-agency/koos-agents`.
