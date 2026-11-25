# Statistically Inevitable

A silly little quiz built to settle an argument: **if you randomly guess on 100 multiple-choice questions with 4 options each, how likely are you to get at least one right?**

The questions are in Spanish. The rest of the game is in English. Choose an answer for each question and submit the quiz to see your score and the answer key—there is no feedback while you play.

## The probability

Assuming each question has exactly one correct answer and you guess independently, the probability of getting a single question wrong is `3/4`. Therefore, the probability of getting all 100 wrong is:

\[
P(\text{100 wrong})=\left(\frac34\right)^{100}
\]
**P(getting at least 1 correct) = 99.999999999968%**

The chance of getting all 100 wrong by random guessing is approximately **1 in 3.12 trillion**. The expected score from random guessing is 25 out of 100.

## Play locally

Open `index.html` in your browser. No dependencies, installation, or build step required.

## Host it on GitHub Pages

1. Create a GitHub repository and upload `index.html` and this README to its root.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your game should be available at `https://<your-username>.github.io/<repo-name>/` once deployment finishes.

## Edit the questions

Questions are in the `Q` array in `index.html`, in the format:

`["Question", "Correct answer", "Wrong 1", "Wrong 2", "Wrong 3"]`

The questions and answer options are shuffled on each attempt.
