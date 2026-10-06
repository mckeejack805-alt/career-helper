# Career Helper — project notes

Career matching app for business students (Phase One: web app).

## Links
- Live website: https://mckeejack805-alt.github.io/career-helper/
- Feedback form (Google Form): https://forms.gle/kDyv1gZbmBjHpdnPA
- Repository: https://github.com/mckeejack805-alt/career-helper

## How updates work
- The whole app is one file: `index.html`. GitHub Pages serves it from the `main` branch, root folder.
- To ship a change: edit `index.html`, commit, push to `main`. The site updates in a minute or two.
- The feedback link lives in `const FEEDBACK_URL` near the "feedback" section of the script.
- `const START_WITH_EXAMPLE` controls whether the app opens with the sample student (keep `false` for students).

## Feedback workflow
- Responses collect in the Google Form's Responses tab (export to Google Sheets, then download as CSV/Excel to analyze).
