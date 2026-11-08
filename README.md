# Personalized Lumbar Spine — Interactive Research Explorer

A GitHub Pages-ready interactive companion to the supplied dissertation chapter `ch2.model.tex`. Uses selected original figures from `pics.zip` and concise summaries grounded in the dissertation chapter. The original `.tex` source is deliberately excluded.

## Deploy for free
1. Create a public GitHub repository.
2. Upload the **contents** of this folder to the repository root.
3. Open **Settings → Pages → Build and deployment**.
4. Choose **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
5. Visit the GitHub Pages URL displayed in Settings.

## Preview locally
Run `python3 -m http.server 8000` in this directory and open `http://localhost:8000`. Opening `index.html` directly will not load `content.json` in some browsers.

## Data integrity
No numerical simulation is performed. Switching controls changes the original chapter figures. The reported mesh-convergence percentages and validation observations are sourced from the chapter. Original chapter figures have not been digitized into invented data.

## Before publishing
Add author name, dissertation citation, institutional attribution, references/bibliography, and confirm any third-party figure rights. The complete dissertation chapter and bibliography are not included; add a dissertation citation before publishing.
