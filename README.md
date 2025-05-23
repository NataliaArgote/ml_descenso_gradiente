# Tarea - Modernización de Desarrollo de ML

Este proyecto implementa un modelo de **regresión lineal** utilizando **descenso de gradiente** y **descenso de gradiente estocástico**, con trazabilidad y registro de experimentos usando **MLflow**.

## Archivos

- `descenso_gradiente_completo.ipynb`: notebook principal con todo el desarrollo.
- `datos_lineales.csv`: dataset usado para entrenamiento.
- `requirements.txt`: librerías necesarias para ejecutar el proyecto.

## Cómo correr

1. Instala los requerimientos:

```bash
pip install -r requirements.txt
```

2. Ejecuta el notebook `descenso_gradiente_completo.ipynb` en Jupyter o VS Code.

3. Para visualizar los experimentos:

```bash
mlflow ui
```

Luego ve a `http://localhost:5000` en tu navegador.

## Qué incluye

- Entrenamiento de regresión lineal (GD y SGD)
- Registro de parámetros y métricas
- Guardado de modelos (`theta.npy`)
- MLflow tracking con múltiples runs