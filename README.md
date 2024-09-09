# Predicting Goals in Manchester Derbies

This project uses machine learning to predict the number of goals scored in football matches between Manchester City and Manchester United (Manchester derbies).

## Dataset

The project uses a dataset containing historical match data, including features like:

* **Team and opponent:** Manchester City and Manchester United.
* **Venue:** Home or away.
* **Formation:** Team formation.
* **Captain:** Team captain.
* **xg:** Expected goals.
* **xga:** Expected goals against.
* **poss:** Possession.
* **sh:** Shots.
* **sot:** Shots on target.
* **dist:** Average shot distance.
* **fk:** Free kicks.
* **pk:** Penalties.
* **pkatt:** Penalty attempts.
* **Target variable:** Number of goals scored in the match.

## Model

A Random Forest Regressor model is used to predict the number of goals. The model is trained on a subset of the data and evaluated on a held-out test set.

## Evaluation

The model's performance is evaluated using metrics such as:

* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**

## Results

The model achieved the following scores on the test set:

* MAE: 0.3
* MSE: 0.14
* RMSE: 0.38

These scores indicate that the model's predictions are relatively accurate, but further analysis and comparison to a baseline model are needed to assess its true performance.

## Example Predictions

The model generated the following predictions for three matches:

* Match 1: 0.39 goals
* Match 2: 1.92 goals
* Match 3: 0.21 goals

These predictions can be interpreted as the expected number of goals for each match.

## Future Work

* Explore other regression models, such as Poisson regression, which might be more suitable for predicting counts.
* Feature engineering to create more informative features.
* Hyperparameter tuning to optimize the model's performance.
* Incorporate additional data sources, such as player statistics or betting odds.

## Conclusion

This project demonstrates the potential of machine learning for predicting the number of goals in football matches. The developed model can be used to gain insights into the factors that influence goal scoring and potentially make more informed predictions about future matches.
