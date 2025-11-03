## Hangman Solver using Hidden Markov Model (HMM) and Reinforcement Learning (RL)

A Hangman solver that combines an OOV HMM, and a RL Model, where the HMM provides probabilities of each letter and the RL Model does all the decision making.

### What It Does

-Trains a HMM on corpus.txt.
-Trains a RL agent with reward shaping.
-Evaluates on test.txt and writes plots + metrics.

### Files & Folders
```text
data/
  corpus.txt    # training words (A–Z only)
  test.txt      # evaluation words
outputs/
  hmm.pkl
  rl_agent.pkl
  training_curves.png
  eval_results.json
hangman_hmm_rl_hybrid.py
requirements.txt
```