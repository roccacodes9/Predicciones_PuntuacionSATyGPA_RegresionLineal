Análisis de Regresión: Impacto de la Asistencia en el Rendimiento Académico
Requisitos:

    Python (3.x)
    Librerías: NumPy, Pandas, statsmodels, Matplotlib, Seaborn

Detalles del Análisis:

En este análisis, se exploró la relación entre el rendimiento académico de los estudiantes universitarios, medido por el GPA (Promedio de Puntos de Grado), y sus puntajes en el examen SAT (Test de Aptitud Académica), así como el impacto de la asistencia a clase en este rendimiento.

    Preprocesamiento de Datos:
        Se cargaron los datos desde un archivo CSV.
        Se convirtió la variable categórica "Attendance" en numérica (0 para "No" y 1 para "Yes").
        Se realizó una descripción inicial de los datos para comprender su distribución y estadísticas resumidas.

    Modelado de Regresión:
        Se utilizó el método de Mínimos Cuadrados Ordinarios (MCO) para ajustar un modelo de regresión lineal.
        La variable dependiente (y) fue el GPA, mientras que las variables independientes (x) fueron los puntajes SAT y la asistencia a clase.
        Se imprimió un resumen detallado del modelo de regresión, que incluye coeficientes, estadísticas de ajuste y significancia de las variables.

    Visualización de Datos:
        Se crearon gráficos de dispersión para visualizar la relación entre SAT y GPA, coloreando los puntos según la asistencia.
        Se trazaron líneas de regresión separadas para estudiantes que asistieron y los que no.
        Se generaron gráficos adicionales para mostrar las líneas de regresión sin considerar la variable de asistencia.

    Predicciones:
        Se realizaron predicciones de GPA utilizando el modelo de regresión ajustado para nuevos datos (SAT y asistencia) utilizando el método predict.
        Se generó un DataFrame que incluye las predicciones junto con los datos originales.

Resultado del Análisis:

El análisis reveló una relación positiva entre los puntajes SAT y el GPA, y también mostró que la asistencia a clase tiene un impacto significativo en el rendimiento académico. Los estudiantes que asisten regularmente tienden a tener un GPA más alto en comparación con aquellos que no asisten con regularidad. El modelo de regresión lineal ajustado proporciona una herramienta para 
