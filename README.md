# Zuber: Análisis de datos de viajes en Chicago

Este proyecto analiza datos de viajes en taxi en Chicago durante noviembre de 2017, con el objetivo de entender el comportamiento de los usuarios y evaluar si las condiciones climáticas afectan la duración de los viajes.

## Objetivos principales

- Identificar las rutas más populares entre barrios.
- Analizar las empresas con mayor participación en viajes.
- Evaluar si el clima influye en la duración de los viajes al aeropuerto.
- Proponer ideas para optimizar el negocio basado en patrones de demanda.

## Prueba de hipótesis

> ¿El mal clima afecta significativamente la duración de los viajes hacia el Aeropuerto O’Hare desde Loop los sábados?

✅ **Resultado:** Sí. Los viajes con mal clima duran **~21% más** en promedio.

## Conclusiones y recomendaciones

- Los viajes con mal clima son significativamente más largos. Esto debe considerarse para estimaciones de tiempo y precios.
- Flash Cab y Taxi Affiliation dominan el mercado. Analizar sus patrones puede ser clave.
- Se recomienda explorar rutas compartidas en trayectos frecuentes (como Loop → Aeropuerto) para aumentar ganancias y optimizar recursos.
- Marketing dirigido en barrios con alta frecuencia de salidas (no solo destinos) puede mejorar la eficiencia de la cobertura.

## Estructura del repositorio

Zuber/
│
├── Data/
│   ├── project_sql_result_01.csv
│   ├── project_sql_result_04.csv
│   └── project_sql_result_07.csv
│
├── Notebooks/
│   └── zuber_analysis.ipynb
│
├── zuber_env.yml
├── README.md
└── zuber_analysis.pdf 

## Tecnologías usadas

- Python, pandas, matplotlib, seaborn
- Jupyter Notebook
- Pruebas estadísticas con `scipy`
- Análisis exploratorio y visualización de datos

## ✨Autor

Anakaren Salinas - [LinkedIn](https://www.linkedin.com/in/anakarensalinas/) 