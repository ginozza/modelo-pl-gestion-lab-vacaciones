# modelo-pl-gestion-lab-vacaciones

Planificación y selección de jornadas de laboratorio durante el periodo de vacaciones en la Universidad del Magdalena; incluye procesamiento de respuestas de sondeos, modelos de programación lineal (maximizar demanda y maximizar cobertura) y resultados reproducibles.

1. Objetivo del proyecto
------------------------
Este proyecto busca determinar, mediante modelos de programación lineal entera, las tres jornadas semanales óptimas para abrir el laboratorio en vacaciones, considerando restricciones operativas (una jornada por día, exactamente 3 jornadas, al menos una mañana y una tarde) y dos criterios: maximizar demanda total o maximizar cobertura estudiantil.

2. Estructura del repositorio
----------------------------
- `data/`              : datos del sondeo (entrada)
- `notebook/`          : notebooks con análisis e implementación (`01_Modelo_Programacion_Lineal.ipynb`)
- `results/`           : gráficos y tablas generadas por el análisis
- `report/`            : documento final
- `requirements.txt`   : dependencias del proyecto

3. Cómo replicar el proyecto
---------------------------
Requisitos previos: Python 3.10+, Git.

Clonar el repositorio:

`git clone <repo-url>`
`cd modelo-pl-gestion-lab-vacaciones`

Crear y activar entorno (Windows PowerShell):

`python -m venv venv`
`.
\venv\Scripts\Activate.ps1`

Instalar dependencias:

`pip install -r requirements.txt`

Ejecutar el notebook `notebook/01_Modelo_Programacion_Lineal.ipynb` en Jupyter o VS Code para reproducir el preprocesamiento, la resolución de modelos y la generación de resultados en `results/`.

4. Notas
--------
- Los resultados generados se guardan en `results/tablas/` y `results/graficos/`.

