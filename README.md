# AI Mastery Interface

A set of short, hands-on activities that teach teachers and students to question, test and trust AI. The site opens with an intro screen, then a module-select page with one card per tool.

## Modules

- **Module 01: AI Threat Scanner** (`threat-scanner/`). A 15-minute activity that teaches how to evaluate the privacy and security of AI tools before trusting them with real use.
  - **Scan:** practice spotting risky and missing language in sample AI-tool policies, using three lenses: Data, Rules and Sight. Part A and Part B are separate pages with a results page between them.
  - **Adaptive ladder:** everyone starts at an Easy level. The activity recommends an easier or harder scenario based on results, with badges. There is no timer and no leaderboard.
  - **Field test:** a self-contained check of a real tool (ChatGPT, Gemini, Canva or Claude) using short evidence summaries on the page. Advanced learners can bring their own tool with Manual or the in-browser Policy Analyzer.
  - **Clearance Card:** a three-part card with a rank for Part A, a rank for Part B, and a verdict for the real-tool Field test.
  - **Operator guide:** a run of show and discussion questions for facilitators.

## Privacy

Everything runs in the browser. No data is sent anywhere by the activities themselves. The Policy Analyzer matches phrases in pasted text locally and does not use AI. Pilot feedback is only collected if a person chooses to copy their summary and paste it into the feedback form.

The pages load fonts from Google Fonts. If your school blocks that, they fall back to system fonts.

## Important

These are teaching activities, not legal advice. Results are exercise results, not district approval. Tool notes in the Threat Scanner were gathered from public pages in October 2026 and can go out of date. Always confirm with your district's technology office.

## Files

- `index.html`: the intro screen and module-select page.
- `threat-scanner/index.html`: Module 01, the whole activity in one file (no build step, no dependencies).

## Publish with GitHub Pages

1. Create a new public repository on GitHub (for example `ai-mastery-interface`).
2. Upload everything in this folder, keeping the structure: `index.html`, `README.md` and the `threat-scanner` folder (drag the files and the folder into the upload page, then commit).
3. Open the repository's Settings, then Pages. Under "Build and deployment," choose "Deploy from a branch," pick `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://YOUR-USERNAME.github.io/ai-mastery-interface/`.

To add or update a module later, upload its folder (or a new `index.html` inside it) to the same repository. To preview locally without GitHub, open `index.html` in a browser.
