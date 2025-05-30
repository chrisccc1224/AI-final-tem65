## Overview
This project is a movie rating prediction model. We used metadata related to the movie instead of review feeding in random forest to predict the score on IMDb, which is a famous movie rating platform. According to the result we used MSE and R^2 score to evaluate.
We also conducted experiments to test the model's performance under different parameters, and visualized the results with charts for easier analysis.

## Prerequisites
- Python 3.13.2
- pandas 2.2.3
- scikit-learn 1.6.1
- numpy 2.2.3
- matplotlib 3.10.1
- tqdm 4.67.1

You can install all required packages using:

```
pip install -r requirements.txt
```
## Usage
- run the block in the main.ipynb with comment main
- if want to try each experiment, run the block with corresponding comment

## Hyperparameters
- n_tree = 40
- max_depth = 19
- max_features = 23

## Experiment results
- MSE = 0.4256
- R^2 = 0.6348
- experiment outcome can be reached in report 

## Reference
- https://www.youtube.com/watch?v=J4Wdy0Wc_xQ
- https://axk51013.medium.com/%E4%B8%8D%E8%A6%81%E5%86%8D%E5%81%9Aone-hot-encoding-b5126d3f8a63
- https://tomohiroliu22.medium.com/%E6%A9%9F%E5%99%A8%E5%AD%B8%E7%BF%92-%E5%AD%B8%E7%BF%92%E7%AD%86%E8%A8%98%E7%B3%BB%E5%88%97-37-%E9%9A%A8%E6%A9%9F%E6%A3%AE%E6%9E%97%E5%9B%9E%E6%AD%B8-random-forest-regressor-a0f7a57c06c4
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
