# El examen imposible

100 general-knowledge questions in Spanish, 4 options each, built to settle one argument:
how likely is it to get **all 100 wrong** by guessing?

Each wrong answer has a 3/4 chance, so the odds are (3/4)^100 ≈ 3.2 × 10⁻¹³, about **1 in 3.1 trillion**.
Expected score from pure guessing: about 25 / 100.

Questions and answer positions are shuffled on every attempt. Works on phones and desktops. No dependencies, no build step.

## Run it locally

Open `index.html` in a browser.

## Host it on GitHub Pages

1. Create a new repository and add `index.html` and this README to the root.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Edit the questions

Questions live in the `Q` array in `index.html`. Each one is
`["Question", "Correct answer", "Wrong 1", "Wrong 2", "Wrong 3"]`; the correct answer is always listed first and the options are shuffled at runtime.
