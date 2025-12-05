#  Segmentación de Clientes de Seguros con DBSCAN
 <img width="1800" height="379" alt="image" src="https://github.com/user-attachments/assets/e45a0358-fedb-404c-9eb1-cafd6117ab8a" />

##  Descripción

Proyecto de Machine Learning que aplica el algoritmo de clustering **DBSCAN** (Density-Based Spatial Clustering of Applications with Noise) para segmentar clientes de una compañía de seguros médicos.

##  Dataset

**Insurance.csv** - Dataset de seguros médicos con 1,337 registros y 7 variables:

| Variable | Tipo | Descripción |
|----------|------|-------------|
| age | Numérica | Edad del asegurado (18-64) |
| sex | Categórica | Género (male/female) |
| bmi | Numérica | Índice de Masa Corporal |
| children | Numérica | Número de dependientes |
| smoker | Categórica | Fumador (yes/no) |
| region | Categórica | Región de residencia |
| charges | Numérica | Cargos del seguro médico |

##  Objetivo

Aplicar aprendizaje no supervisado (DBSCAN) para:
- Segmentar clientes en grupos homogéneos
- Identificar patrones de comportamiento
- Detectar casos atípicos (outliers)

##  Metodología

1. Carga y descripción del dataset
2. Preprocesamiento y limpieza
3. Análisis exploratorio (EDA)
4. Estandarización con StandardScaler
5. Reducción de dimensionalidad (PCA)
6. Aplicación de DBSCAN
7. Tuning de hiperparámetros
8. Evaluación del modelo
9. Conclusiones

##  Resultados

| Métrica | Valor |
|---------|-------|
| Clusters encontrados | 2 |
| Silhouette Score | 0.668 |
| Davies-Bouldin Index | 0.542 |
| Puntos de ruido | 8 (0.6%) |

**Clusters identificados:**
- **Cluster 0** (20.8%): Clientes de alto riesgo
- **Cluster 1** (78.6%): Clientes estándar

##  Tecnologías

- Python 3.12.9
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

##  Estructura

```
├── insurance.csv           # Dataset
├── RUBEN_CASA_EP1.ipynb    # Notebook principal
└── README.md               # Documentación
```

##  Autor

**Rubén Casa**

## Licencia

Este proyecto es de uso académico.

