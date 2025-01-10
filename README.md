# mlb-ops-predictions
Predicting MLB player OPS using multiple linear regression and 12 batting metrics. Includes data analysis, visualizations, and evaluation metrics to assess model accuracy and explore player potential.
# Predicting MLB Batting Performance with OPS

## Project Overview
This project analyzes the relationship between 12 MLB batting metrics and a batter's OPS (on-base plus slugging). Using multiple linear regression, it aims to predict OPS based on secondary metrics, offering insights for scouts, teams, fans, and players.

## Motivation
OPS is a widely used metric for evaluating overall batting performance. By predicting OPS using other statistics, this project helps identify player potential, optimize team lineups, and inform decision-making in scouting and player development.

## Data
The dataset was sourced from [Baseball Savant](https://baseballsavant.mlb.com), including:

- Years: 2019, 2021-2024 (excluding 2020 due to the shortened season)
- Minimum plate appearances: 502
- Metrics: Singles, doubles, triples, home runs, strikeouts, walks, batting average, runs batted in, total bases, stolen bases, barrel percentage, and in-zone percentage

### Ethical Considerations
The data is publicly available and devoid of personal information, ensuring no ethical or privacy concerns.

## Methodology
- **Model:** Multiple Linear Regression
- **Evaluation Metrics:**
  - Mean Squared Error (MSE): Measures the accuracy of predictions.
  - R-squared: Evaluates the variance explained by the model.

## Results
- **Mean Squared Error:** 0.00008457, indicating high accuracy.
- **R-squared:** 0.9900, showing that 99% of OPS variance is explained by the model.

Visualizations include:
- Scatter plot comparing predicted and actual OPS values.
- Pair plot showing correlations between independent variables and OPS.

## Key Findings
The model successfully predicts OPS with high accuracy, demonstrating the strong relationship between the chosen metrics and a player's offensive performance.

## Future Work
- **Pitching Analysis:** Develop a similar model to predict pitcher performance using metrics like ERA.
- **Expanded Metrics:** Explore additional statistics to enhance the current model.

## Repository Contents
- **Data:** CSV files sourced from Baseball Savant.
- **Code:** Jupyter Notebook for data preprocessing, model training, and evaluation.
- **Visualizations:** Scatter plots and pair plots showcasing results.

## Getting Started
1. Clone the repository:
   ```bash
   git clone <repo-url>
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook to run the analysis:
   ```bash
   jupyter notebook mlb_ops_prediction.ipynb
   ```

## Acknowledgments
- Data sourced from [Baseball Savant](https://baseballsavant.mlb.com).
- This project was created as part of a data science course at Northeastern University.
