# My portfolio
## Take a look at my projects! 
### [Project 1: Can Machine Learning Beat the Odds?](https://github.com/BMAS30/Can-Machine-Learning-Beat-the-Odds-)

This project tested whether machine learning can outperform bookmakers in Hong Kong horse racing using historical data (up to 2005).
After cleaning and encoding race features—like jockey, trainer, weights, and odds—we trained several models, with LightGBM delivering the best predictive accuracy and betting simulation results.
Simulations showed that, in some races—especially when the market lacked a clear favorite, the model slightly outperformed the “bet on the favorite” strategy, particularly when applying a probability threshold to filter bets. 
I tried also alternative “place” bet approach which improved hit rates but was unprofitable due to low payouts.
While not a guaranteed money-maker, the model detected instances where market odds underestimated true win probabilities. With updated data, richer features, and refined selection criteria, there’s potential to better exploit these inefficiencies.  


### [Project 2: Using machine learning in goals market.](https://github.com/BMAS30/Using-machine-learning-in-goals-market)

This project tested whether a machine learning model can beat the Over/Under 2.5 goals market in Premier League football. 
Using historical data and engineered features like recent form, goal averages, and win rates, an XGBoost model was trained with walk-forward validation to simulate real-time predictions for the 2024–25 season.

Two strategies were compared:

A base line that bet on the model’s higher probability side with no value filter.
A value betting approach that placed bets only when the expected value exceeded a set threshold.

The baseline produced inconsistent results due to betting without edge. The EV-filtered strategy, especially with a 1.50 threshold, reduced marginal bets and improved ROI by focusing on the most mispriced odds. 


### [Project 3: Exploring Data jobs using SQL](https://github.com/BMAS30/Data-Jobs-SQL-project)

This project analyzes job market data to identify the most in-demand and best-paying skills for data-related roles, as well as the optimal combination of skills that maximize both employability and salary potential. The analysis is supported by SQL queries applied to job postings datasets.
