# Statistically Inevitable

A silly little quiz built to settle an argument: **if you randomly guess on 100 multiple-choice questions with 4 options each, how likely are you to get at least one right?**

The questions are in Spanish. The rest of the game is in English. Choose an answer for each question and submit the quiz to see your score and the answer key—there is no feedback while you play.

## The probability

Assuming each question has exactly one correct answer and you guess independently, the probability of getting a single question wrong is `3/4`. Therefore, the probability of getting all 100 wrong is:



### The Probability

The probability of getting all 100 questions wrong:

$$
P(\text{100 wrong}) = \left(\frac{3}{4}\right)^{100}
$$

`P(wrong) = (3/4)^100 ≈ 3.2 × 10⁻¹³`


The probability of getting at least one correct answer:

$$
P(\text{at least 1 correct}) = 1 - \left(\frac{3}{4}\right)^{100}
$$

`P(at least 1 correct) = 1 - (3/4)^100`


**99.999999999968%**

The chance of getting all 100 questions wrong by random guessing is approximately **1 in 3.12 trillion**.



**P(getting at least 1 correct) = 99.999999999968%**

The chance of getting all 100 wrong by random guessing is approximately **1 in 3.12 trillion**. The expected score from random guessing is 25 out of 100.

## Play locally

Open `index.html` in your browser. No dependencies, installation, or build step required.



The questions and answer options are shuffled on each attempt.
