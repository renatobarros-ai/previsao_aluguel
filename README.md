# Desenvolvimento de Modelo para Previsão de Valor de Aluguel

Para este projeto, utilizei os dados de aluguel disponibilizados para construir um modelo que prevê o valor de aluguel de imóveis.

O projeto iniciou-se com a coleta, limpeza e transformação dos dados, aplicando-se técnicas como transformação logarítmica, PowerTransformer, Target Encoding e seleção de features.

Em seguida, diversos algoritmos de regressão (Linear, Ridge, Lasso, ElasticNet, SGDRegressor, DecisionTreeRegressor, RandomForestRegressor, KNeighborsRegressor, GaussianProcessRegressor) foram treinados e avaliados por mim, otimizando-se os hiperparâmetros com GridSearchCV e validação cruzada (5-fold). O Random Forest apresentou o menor RMSE.

Para aprimorar ainda mais a precisão, criei um ensemble combinando as previsões de diferentes modelos (Lasso, ElasticNet, Random Forest e SGDRegressor).
