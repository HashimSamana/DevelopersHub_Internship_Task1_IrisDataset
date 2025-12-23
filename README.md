# Task 1: Exploring and Visualizing the Iris Dataset

## Objective
Understand the Iris dataset by summarizing, visualizing relationships between features, and detecting outliers.

## Dataset
- Iris Dataset (available via seaborn or Kaggle)
- Features: SepalLength, SepalWidth, PetalLength, PetalWidth, Species

## Approach
1. Load dataset using pandas
2. Inspect dataset structure: `.shape`, `.columns`, `.head()`
3. Visualizations:
   - Scatter plots to analyze relationships between variables
   - Histograms to examine feature distributions
   - Box plots to detect outliers
4. Use seaborn and matplotlib for visualization

## Results & Insights
- PetalLength and PetalWidth are strongly correlated
- Outliers detected in SepalWidth
- Species can be distinguished based on petal dimensions

## Libraries Used
pandas, matplotlib, seaborn
