# Career Mentor

A free career planning website: explore 121 careers in 10 streams, take an interest quiz, compare careers, follow a 15-stage roadmap for each career, check a resume for ATS (applicant tracking system) readiness, build a resume, practise interview answers, and track applications.

It is a plain static website (one `index.html` plus a `vendor/` folder). There is no server, no database, no API key and no sign-up. Progress is saved in the visitor's own browser.

## Put it live on GitHub Pages (free)
1. Create a new repository on github.com (Public).
2. Upload everything in this folder (`index.html`, `vendor`, `README.md`, `.gitignore`). `index.html` must be at the top level.
3. Open the repository, then Settings, then Pages. Under Branch choose `main` and the `/ (root)` folder, then Save.
4. Wait a minute or two. GitHub shows your live address, for example `https://YOUR-NAME.github.io/YOUR-REPO/`.

Updating later: edit or upload the file on GitHub and commit. The site refreshes by itself.

## Run it on your computer
Double-click `index.html`. Everything works, including PDF reading in the resume checker (the PDF reader is loaded as plain scripts from the `vendor/` folder, so keep that folder next to `index.html`). You can also serve it with `python -m http.server 8000` and open `http://127.0.0.1:8000`.

## Good to know
- Profiles are per browser and per device. Use Toolkit, then Download backup, to keep a copy or move to another device.
- Career information is general guidance for India. Eligibility, fees and dates change, so confirm on the official website.
- PDF reading uses PDF.js (Apache License 2.0), included in `vendor/` with its licence.
- External links in the career pages and Toolkit open official websites. Their addresses can change over time.
