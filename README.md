# Diamond Price Prediction

El objetivo de este proyecto es predecir el precio de los diamantes sobre un dataset desconocido.

Partimos de un dataset con diferentes características de los diamantes y sus precios. Una vez llevada a cabo la limpieza de los datos, se han aplicado los siguientse modelos de predicción:

- GradientBoostingRegressor
- HistGradientBoostingRegressor
- LinearRegression
- RandomForestRegressor
- XGBRegressor
- LinearSVR
- ElasticNet

El modelo que mejor resultados ha presentado es RandomForestRegressor con un RMSE = 551.42623