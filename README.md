# MSCS 634 Lab 2: Classification Using KNN and RNN Algorithms

## Purpose
This lab explores classification using K-Nearest Neighbors (KNN) and Radius Neighbors (RNN) classifiers on the Wine dataset from `sklearn`. The goal is to compare how different `k` and `radius` hyperparameters affect accuracy and determine when each method is preferable.

## Key Insights
- KNN accuracy was measured for `k = 1, 5, 11, 15, 21`.
- RNN accuracy was measured for `radius = 350, 400, 450, 500, 550, 600`.
- KNN performance typically depends on selecting a moderate `k` to balance sensitivity and generalization.
- RNN performance is influenced by the radius scale; very large radii can cause predictions to rely on a wide neighborhood.

## Notes
- The notebook includes dataset exploration, train/test splitting, model training, accuracy reporting, and visualization.
- Use the notebook file `MSCS_634_Lab_2_Classification_KNN_RNN.ipynb` for the full lab analysis.
