# FC26 Player Data Analysis

## Project Overview

This project analyzes FIFA 26 player data to uncover insights into player attributes, roles, and potential. Using machine learning techniques like clustering, PCA, and regression, it aims to classify players, predict potential, and find similar players. However, as a devil's advocate, one must question whether this analysis truly captures the essence of football talent or merely reinforces statistical biases in a game that's ultimately about human performance on the pitch.

## Features

- **Data Exploration**: Visualizations of player distributions, correlations, and outliers.
- **Feature Engineering**: Creation of composite scores for attacking, playmaking, and defensive abilities.
- **Dimensionality Reduction**: PCA to simplify player skill profiles into 2D space.
- **Clustering**: K-Means clustering to group players into archetypes (e.g., strikers, defenders).
- **Predictive Modeling**: XGBoost regression to predict player potential, with hyperparameter tuning.
- **Similarity Analysis**: Cosine similarity for recommending similar players.

But let's be critical: These features rely heavily on in-game stats that may not reflect real-world performance. FIFA ratings are subjective and can perpetuate stereotypes about player abilities based on nationality, age, or position.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/FC26-Player-Data-Analysis.git
   cd FC26-Player-Data-Analysis
   ```

2. Install dependencies (assuming Python 3.8+):
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
   ```

3. Ensure you have the dataset: `FC26.csv` should be in the project directory.


## Usage

1. Open `FCplayer.ipynb` in Jupyter Notebook or VS Code.
2. Run cells sequentially to explore data, build models, and generate visualizations.
3. Example: Predict potential for a player or find similar players.