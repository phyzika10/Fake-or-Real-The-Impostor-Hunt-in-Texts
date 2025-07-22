# Fake or Real: The Impostor Hunt in Texts - Final Ensemble Voting

This dataset contains the final ensemble predictions and visualizations used in the Kaggle competition **"Fake or Real: The Impostor Hunt in Texts"**.

## Contents

- `submission_postprocessed.csv`: The final submission file using weighted voting with post-processing from top models.
- `voting_distribution.png`: Visualization showing the distribution of predicted classes.
- `correlation_matrix.png`: Heatmap of prediction correlations between the 5 models.

## Ensemble Strategy

We blended the predictions from 5 high-scoring public models using a weighted voting approach based on their public leaderboard performance:

- Model 1: Weight 0.35 
- Model 2: Weight 0.30 
- Model 3: Weight 0.15
- Model 4: Weight 0.10
- Model 5: Weight 0.10

We applied **post-processing** by overriding predictions when **Model 1 and Model 2 agree**, to enhance accuracy based on empirical observation.

## Visual Insights

- **Voting Distribution:** Shows class balance after ensemble.
- **Correlation Matrix:** Measures similarity among model predictions.

## Reproducibility

The ensemble was built using `pandas`, `matplotlib`, and `seaborn` in a Kaggle notebook environment. All required steps, visualizations, and outputs are included here.

## Author

Mohamed Zakaria – Egypt Data Scientist Team 🇪🇬  
📅 July 2025
