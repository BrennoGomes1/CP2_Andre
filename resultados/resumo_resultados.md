## Resultados obtidos (gerado pelo notebook)

### Tarefa 1: Classificação (teste estratificado 20%, semente 42, métricas com média macro)

Linhas usadas: 3876 | treino: 3100 | teste: 776

| Modelo | Accuracy | Precision (macro) | Recall (macro) | F1 (macro) | F1 (weighted) |
|---|---|---|---|---|---|
| Random Forest | 0.976 | 0.977 | 0.974 | 0.975 | 0.975 |
| KNN (k=7) | 0.965 | 0.966 | 0.964 | 0.964 | 0.965 |
| Regressão Logística | 0.834 | 0.850 | 0.830 | 0.829 | 0.833 |

**Melhor modelo (F1 macro):** Random Forest.

### Tarefa 2: Regressão (treino: primeiras 80% das horas; teste: últimas 20%)

Horas usadas: 1001 | treino: 800 | teste: 201

| Modelo | MAE (W/m²) | MSE ((W/m²)²) | RMSE (W/m²) | R² |
|---|---|---|---|---|
| Random Forest Regressor | 67.19 | 7,419.60 | 86.14 | 0.84 |
| KNN Regressor (k=10) | 72.18 | 8,222.93 | 90.68 | 0.82 |
| Regressão Linear | 145.20 | 30,034.20 | 173.30 | 0.36 |

**Melhor modelo (R²):** Random Forest Regressor.
