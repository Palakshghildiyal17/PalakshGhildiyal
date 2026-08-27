# CS6.302 — HTML/CSS Assignment Kit

Files in this folder:

- **index.html** — your personal GitHub Pages site (About, Education, Work
  Experience, Skills/Interests, Hobbies, Picture Gallery, Contact). Fully
  self-contained: styling is in a `<style>` block, images are inline SVG
  placeholders so it works before you add real photos.
- **ssdcoursepage.css** — a stylesheet that restyles the "boring" SSD course
  page (dark theme, pill-style nav, card-style tables, zebra striping,
  hover states) using only generic tag selectors, so it does not require
  changing any existing HTML content.
- **rollnumber_htcs.txt** — the submission file template; rename it to
  `<yourrollnumber>_htcs.txt` and fill in your URLs.

## Part 1 — Personal github.io page

1. Create a repo named exactly `<your-github-username>.github.io`.
2. Edit `index.html`:
   - Replace every "Your Name", "2026XXXXX", timeline, experience, skills,
     and contact placeholder with your real details.
   - Swap the inline SVG `<img>` placeholders in the Hero and Gallery
     sections for real photos (e.g. `assets/profile.jpg`).
3. Push `index.html` (and an `assets/` folder for images) to the repo's
   `main` branch.
4. Enable Pages: repo **Settings → Pages → Source: main branch, / (root)**.
5. Your site goes live at `https://<your-github-username>.github.io/`.

## Part 2 — Beautify the SSD course page

You cannot edit the instructor's repo, so you replicate the page in your
own repo and layer your CSS on top:

1. Save a copy of the course page's HTML as `ssdcoursepage.html` in your repo
   (same content/structure as `https://serc-iiith.github.io/CS6302_M26.html`,
   unmodified).
2. Add `ssdcoursepage.css` to the same repo.
3. In `ssdcoursepage.html`, add **one line** inside `<head>` — this only
   attaches a stylesheet, it does not change any existing element, text,
   or structure:
   ```html
   <link rel="stylesheet" href="ssdcoursepage.css">
   ```
4. Commit and push. It will be live at
   `https://<your-github-username>.github.io/ssdcoursepage.html`.

## Part 3 — Submit

1. Rename `rollnumber_htcs.txt` to `<yourrollnumber>_htcs.txt`.
2. Fill in your two live URLs from Parts 1 and 2.
3. Submit that `.txt` file per the course's submission instructions.
