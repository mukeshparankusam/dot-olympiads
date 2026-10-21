# DOT Olympiads — GitHub Pages Starter

A responsive static website for DOT Olympiads, built for GitHub Pages.

## Files
- `index.html` — website interface and interactions
- `syllabus.json` — 480 topic entries extracted from the provided DOT Olympiads Master Framework (6 subjects × 10 classes × 8 topics)
- `assets/dot-logo.png` — provided DOT Olympiads logo

## Publish with GitHub Pages
1. Create or open the GitHub repository intended for DOT Olympiads.
2. Upload **all files and folders inside this directory** to the repository root. Do not upload only the ZIP file.
3. Commit the files to the `main` branch.
4. In the repository, open **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to finish deploying; the published URL appears in Settings → Pages.

## Important functionality notes
- The syllabus selector, class buttons, subject cards, responsive menu and resource “Coming Soon” dialogs run client-side.
- The institution form currently prepares an email request. It does **not** create a secure database record, verify an institution, allocate institution codes, process payments or lock a registration list.
- The results form is a front-end placeholder until a secure results backend is built.
- Admin and institution login dashboards require authentication, a database and secure server-side logic; they are not implemented by this static package.
- Final privacy, terms, refund and data-handling policies must be approved before collecting personal data online.
- No impact statistics or targets are included.
