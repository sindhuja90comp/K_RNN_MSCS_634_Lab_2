
# K_RNN_MSCS_634_Lab_2

## Purpose
The purpose of this lab is to compare the performance of K-Nearest Neighbors (KNN) and Radius Neighbors (RNN) classifiers using the Wine dataset from the sklearn library.
We analyze how different parameter values (k for KNN and radius for RNN) affect the accuracy of the models.
The lab helps to understand how parameter tuning influences classification results and provides insights into choosing the best model for a given dataset.

## Key Insights from Accuracy Trends and Observations
- KNN Performance: Accuracy varies with the value of k. Smaller k (like 1) may overfit, while larger k values smooth predictions and may improve generalization.
- RNN Performance: Accuracy is highly sensitive to the chosen radius. Very small or very large radius values can reduce accuracy.
- Comparison: KNN showed more stable performance across different k values, while RNN required careful tuning of radius.
- Observation: KNN is easier to tune and often performs better on dense datasets like the Wine dataset. RNN may be more useful for datasets with irregular spacing or varying densities.

## Challenges and Decisions
- Choosing Parameters: Selecting appropriate k values for KNN and radius values for RNN required experimentation to find the best accuracy.
- RNN Sensitivity: RNN performance was highly affected by the radius choice; some values resulted in poor classification or no neighbors.
- Model Comparison: We decided to use accuracy as the main metric for evaluating both models.
- Data Splitting: An 80-20 train-test split was chosen to balance training size and evaluation reliability.


