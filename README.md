# Tarea 3 — Introducción al Aprendizaje Automático (INF398)

**Alumno:** Carlos Ramírez Valdés — ROL 202192826-k  
**Universidad:** Universidad Técnica Federico Santa María  
**Asignatura:** INF398 Introducción al Aprendizaje Automático

---

## Descripción

Notebook Jupyter con la implementación completa de la Tarea 3, que cubre los siguientes tópicos:

| Parte | Tema |
|---|---|
| 1 | Carga de datos, EDA y split estratificado |
| 2 | Random Forest e importancia de variables (MDI y MDA) |
| 3 | Manejo de desbalance de clases (SMOTE, class_weight) |
| 4 | Calibración de modelos (Platt scaling, regresión isotónica) |
| 5 | Red Bayesiana — estructura DAG e inferencia exacta |
| 6 | Procesos Gaussianos — comparación de kernels (RBF, Matérn 3/2) |
| 7 | EM y GMM — selección de K con BIC, clustering de clientes |
| 7b | EM vectorizado (log-sum-exp), segmentación MRI con GMM+MRF |

## Dataset

**Telco Customer Churn** — disponible en [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).  
El archivo CSV **no está incluido** en este repositorio. Descargarlo y colocarlo en la raíz del proyecto antes de ejecutar el notebook.

## Archivos

```
Tarea3_ML.ipynb   — notebook principal (ejecutar en orden)
Tarea3_ML.html    — export HTML con todos los outputs
GMM-EM/           — implementación del profe + imágenes MRI multiespectral (GBM)
.gitignore
```

## Requisitos

```
python >= 3.9
numpy, pandas, matplotlib, scipy, sklearn
imbalanced-learn >= 0.14
pgmpy
cv2 (opencv-python)
```

## Ejecución

1. Descargar el dataset de Kaggle y colocarlo en la carpeta del proyecto.
2. Abrir `Tarea3_ML.ipynb` en Jupyter.
3. **Kernel → Restart & Run All.**
