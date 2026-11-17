# CSE 134B Homework 4 — Alexandro Portfolio

Built on the actual Homework 3 portfolio files. The original cheese exercise is archived in `part1/` and is not an HW4 requirement.

## Graded pages
- `form-no-js.html`: HTML/CSS only, required fields and native validation, POST to httpbin.org/post.
- `form-with-js.html`: progressive enhancement via `form.js`, accessible errors, character count, and serialized `form-errors` history.
- `theme.js`: persistent light/dark theme and same-document View Transition API; not loaded by the no-JS form.
- `style.css`: original HW3 design plus HW4 form/theme/transition styling.

## Deploy and test
1. Create a **new** public HW4 GitHub repository and upload the contents of this directory to its root. Do not overwrite HW3.
2. Create a **new** Netlify deployment from that repository.
3. In Chrome, test the HTML form with JavaScript disabled: missing values, malformed email, short comments, and successful sample POST.
4. Test the enhanced form with JavaScript on: type, blur, failed button and Enter submissions, fix fields, and verify `form-errors` JSON in httpbin response.
5. Test theme toggle on multiple pages, reload, and reduced-motion behavior. With JS off, all pages remain usable and `form-no-js.html` has no scripts.
6. Submit only the new repository URL and deployed site URL to Gradescope.

Note: httpbin is an external testing service; do not enter private information. External endpoint availability cannot be guaranteed.
