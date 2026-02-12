This project focuses on the prediction of the System Price, also known as the
‘imbalance price’, which reflects the real-time cost of balancing the difference between the
contracted and actual generation or consumption of electricity in each half-hourly Settlement
Period (SP). The System Price is paid by market participants (generators, suppliers) who have
a net deficit from their contracted generation/consumption position, or paid to those with a net
surplus from their contracted position

The objective of this project is to evaluate the performances of three different modelsin the prediction 
of System Price, namely Multiple Linear Regression, Random Forest and XGBoost, 
and investigate which variables are impactful predictors on system price. 

XGBoost was the top performer with the lowest MAE of
£21.05/MWh and highest R² of 0.6631, a performance that is on par with other published
papers (Bunn, Inekwe and Macgeehan, 2021). XGBoost also out-performed in the prediction
of price spikes, with a MAE (stress) of £69.53/MWh and F1 score of 0.51. This corroborates
with existing literature that non-parametric models are better than linear regression at
modelling complex non-linear relationship of electricity prices.
6.2. In terms of investigating which variables are impactful predictors, this study found that
Market Index Price was the most influential feature across all three models, while Gas Price
was the second most influential in two out of three of the models. This key insight helps market
participants prioritise which information they should consider in their analysis, especially since
there is a burgeoning amount of data made available as the delivery settlement period
approaches

This study contributes to the growing volume of work on imbalance forecasting. Future
research could shed light on improving prediction accuracy, which is of great importance to
maximise revenue for NIV chasers and battery operators
