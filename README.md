# NBA-Arb-Exploration

This project analyzes NBA game data to identify potential arbitrage opportunities based on historical odds and game outcomes. By comparing moneyline odds across different times (e.g., one day before the game and at game time), it seeks to uncover a thresholds that maximize profitability or In-the-Money (ITM) outcomes.

# Data Collection:
- Incorporates NBA game odds data (moneyline odds one day before the game and at game time).
- Data was gathered on Polymarket, which is an American cryptocurrency prediction market where the odds are determined by market participants.


# Identifying Threshold:
- Identifies 2 different thresholds based on a machine learning approach along with a threshold developed through identifying success rates for different odds
  
# Machine Learning:
- Implements Logistic Regression and Gradient Boosting to predict ITM outcomes.
- Performs hyperparameter optimization to identify the best thresholds for ITM success.



