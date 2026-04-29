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

Critique: Dependencies might conflict with other projects, and the dataset is proprietary (from FIFA), raising copyright concerns. Is it ethical to analyze and share insights from licensed data?

## Usage

1. Open `FCplayer.ipynb` in Jupyter Notebook or VS Code.
2. Run cells sequentially to explore data, build models, and generate visualizations.
3. Example: Predict potential for a player or find similar players.

Devil's advocate view: This notebook is a black box of code without clear reproducibility. What if the models overfit? Or worse, what if scouts use this to undervalue diverse talent, reinforcing systemic biases in football?

## Data Source

The dataset `FC26.csv` contains player attributes from FIFA 26 (released in 2020). It includes stats like pace, shooting, passing, etc., for thousands of players.

Criticism: FIFA data is game-specific and not real match data. It might undervalue players from leagues not well-represented in the game. Moreover, using outdated data (from 2020) for current analysis is misleading – player potentials change over time.

## Limitations and Ethical Concerns

- **Data Bias**: FIFA ratings can be influenced by marketing and sponsorships, not just skill.
- **Over-Simplification**: Reducing players to numbers ignores intangibles like leadership or adaptability.
- **Privacy Issues**: Player data includes personal attributes; ensure compliance with data protection laws.
- **Misuse Potential**: Could be used for discriminatory scouting practices or fantasy sports exploitation.
- **Technical Flaws**: Models may not generalize; clustering assumes distinct archetypes that don't exist in reality.
- **Outdatedness**: Based on FC26, which is years old – football evolves faster than game updates.

As a devil's advocate, this project might do more harm than good by quantifying human athletes in ways that commodify them, ignoring the sport's unpredictability and cultural context.

## Contributing

Feel free to fork and submit pull requests. But think twice: Are we improving football analysis or just gamifying human evaluation?

## License

This project is for educational purposes only. FIFA data is proprietary – do not redistribute.

## Contact

For questions, open an issue. But remember, data analysis isn't truth; it's interpretation.