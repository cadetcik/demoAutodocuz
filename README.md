# AutoDoc UZ — Pitch Day 3.0 demo website

Responsive, static HTML/CSS/JavaScript website with Uzbek, Russian and English translations, a rule-based FAQ chatbot, a team page section, product roadmap, execution plan, and a dedicated `/demo/` page.

## Deploy to GitHub Pages

1. Create a public GitHub repository, e.g. `autodoc-pitchday`.
2. Upload **all contents of this folder** to the repository root, preserving `assets/` and `demo/`.
3. Open **Settings → Pages → Build and deployment → Deploy from a branch**.
4. Choose **main** and **/(root)**, then save.
5. Your site should be available at `https://YOUR-USERNAME.github.io/autodoc-pitchday/` and its demo at `https://YOUR-USERNAME.github.io/autodoc-pitchday/demo/` after GitHub finishes deployment.
6. Submit the deployed `/demo/` or main URL according to the competition instructions.

## Important content notes

- The website describes the product as **in beta testing** (Google Play Console), not publicly launched.
- Team skills are **illustrative defaults based on roles**; replace them with verified skills before submitting if necessary.
- Team illustrations load from DiceBear's external avatar service. Download and host avatar SVGs locally if you need offline use.
- The YouTube demo is embedded via YouTube's privacy-enhanced domain; embedding depends on video permissions and connectivity.
- The FAQ chatbot is **keyword-based with prepared answers**, not a live AI model. No API keys are needed.
- The $45,000 figure is an investment request, not funding already raised.
- Replace or expand the demo-video if the contest requires 1–5 minutes and your linked YouTube Short is shorter than one minute.
- For exact `/demo` (without trailing slash), GitHub Pages normally redirects to `/demo/`.

## Edit

- Main content: `index.html`
- Demo content: `demo/index.html`
- Styling: `assets/style.css`
- Translations and FAQ answers: `assets/app.js`

No build step or backend required.
