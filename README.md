# CSEC 520/620 — Adversarial Machine Learning: Hands-On Self-Study Lab

A self-paced notebook: train a small classifier, then attack and defend it step by step.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/byuan/csec-520-620-advml-lab/blob/main/Adversarial_ML_Lab.ipynb)

## How to start

1. Click **Open in Colab** above and sign in with your RIT Google account.
2. Choose **File → Save a copy in Drive** so your changes and answers are kept.
3. Run the cells in order (`Shift+Enter`). Total compute time is under two minutes on a CPU.

To run locally instead: `pip install torch scikit-learn matplotlib jupyter`, then open `Adversarial_ML_Lab.ipynb`.

## What it covers

| Part | Topic |
|---|---|
| 1 | Train the model you will attack |
| 2 | Evasion with the Fast Gradient Sign Method (FGSM) |
| 3 | A stronger evasion attack: Projected Gradient Descent (PGD) |
| 4 | Defense: adversarial training |
| 5 | Poisoning: planting a backdoor |
| 6 | Model extraction and black-box transfer attacks |
| 7 | Wrap-up: threat models, self-check, extensions |

Each part has a **Predict first** question, a **Try it** task, and **Check your understanding** questions with hidden answers.

## Ground rule

Everything here attacks a model you train yourself. Use these techniques only on systems you own or are authorized to test.
