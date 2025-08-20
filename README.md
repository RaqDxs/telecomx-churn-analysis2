Telecom X - Análisis de Evasión de Clientes (Churn)

Este proyecto corresponde al desafío de Telecom X, donde el objetivo principal es analizar la evasión de clientes (Churn) y descubrir los factores que explican la cancelación de servicios.

El análisis servirá como base para que el equipo de Data Science construya modelos predictivos y proponga estrategias de retención de clientes.

🎯 Objetivos

✔️ Importar y manipular datos desde una API (JSON)
✔️ Aplicar procesos de ETL (Extracción, Transformación y Carga)
✔️ Realizar un Análisis Exploratorio de Datos (EDA)
✔️ Generar visualizaciones estratégicas para identificar patrones
✔️ Elaborar un informe con insights relevantes sobre la evasión

🛠️ Tecnologías utilizadas

Python 3

Pandas → manipulación de datos

Matplotlib & Seaborn → visualización de datos

Jupyter Notebook / Google Colab → análisis interactivo

📂 Estructura del repositorio
telecomx-churn-analysis2/
│── data/
│   └── TelecomX_Data.json      # dataset en formato JSON
│
│── notebooks/
│   └── 01_extraccion_datos.ipynb   # carga de datos desde la API
│   └── 02_limpieza_eda.ipynb       # limpieza + EDA
│
│── src/
│   └── etl.py        # funciones ETL
│   └── utils.py      # utilidades auxiliares
│
│── reports/
│   └── informe_final.md   # conclusiones e insights del análisis
│
│── requirements.txt   # dependencias del proyecto
│── README.md          # documentación principal

📥 Datos

Los datos provienen de la API en formato JSON:
🔗 TelecomX_Data.json

🚀 Ejecución del proyecto

Clonar el repositorio:

git clone https://github.com/RaqDxs/telecomx-churn-analysis2.git
cd telecomx-churn-analysis2


Crear un entorno virtual (opcional):

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows


Instalar dependencias:

pip install -r requirements.txt


Abrir los notebooks en Jupyter Notebook o Google Colab y ejecutar los análisis.

📊 Resultados esperados

Variables clave asociadas a la evasión de clientes.

Visualizaciones claras de las tendencias de cancelación.

Conclusiones que permitan proponer estrategias de retención.

👩‍💻 Autor

Repositorio desarrollado por RaqDxs
 ✨
Parte del programa One | Alura + Oracle.
