# telecom-analysis-S7project
Este repositorio contiene el análisis realizado sobre el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones en Latinoamérica.

El proyecto utiliza información registrada hasta el año 2024 para explorar la calidad de los datos, analizar el comportamiento de los clientes y generar segmentos de usuarios que apoyen la toma de decisiones del negocio.

**📂 Contenido del repositorio**
telecom-analysis-S7project/S7 Version-Estudiante-Project-ConnectaTel.ipynb → Notebook principal con limpieza de datos, análisis exploratorio (EDA), segmentación de clientes, detección de outliers y conclusiones.
Cómo abrir el notebook en Google Colab

Haz clic en el botón

*[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/micaelamorane/telecom-analysis-S7project/blob/main/Project-ConnectaTel.ipynb)* 

o:

- Abre el archivo .ipynb en GitHub.
- Haz clic en **Open in Colab**.

**📘 Cómo reproducir el análisis**
- Abre telecom-analysis-S7project/S7 Version-Estudiante-Project-ConnectaTel.ipynb
- Ejecuta las celdas en orden.
- El notebook carga automáticamente los siguientes datasets:
  - plans.csv
  - users.csv
  - usage.csv

**📊 Datasets utilizados**
- plans.csv → Información de los planes disponibles (precio, minutos incluidos, GB incluidos y costo por consumo adicional).
- users.csv → Información de los clientes (edad, ciudad, fecha de registro, plan contratado y estado de churn).
- usage.csv → Registro del uso real de los servicios (llamadas y mensajes).

**🧠 Objetivo del análisis**
- Evaluar la calidad de los datos y realizar su limpieza.
- Construir un perfil estadístico de los clientes.
- Identificar segmentos según edad y nivel de uso.
- Detectar patrones de consumo y valores atípicos.
- Generar insights para apoyar estrategias de retención y proponer mejoras en la oferta de planes de ConnectaTel.
