# Cartpole-Practice
ME 597 - Case Study 2

Goal: beat the hand-written policy from the lecture (about 42 steps) using tabular Q-learning.

CartPole's state is four continuous numbers, but a Q-table needs a finite list of states. So before Q-learning can run, you decide how to cut each number into bins. That choice turns out to matter a lot.

Your two tasks:

- Fill in the Q-learning update in Cell 3 (one line).
- Try a few choices of BINS in Cell 2 (at least 3 sets), retrain, and write your best score on the board with the bins you used.
