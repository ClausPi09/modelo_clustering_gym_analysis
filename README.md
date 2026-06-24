# Proyecto Modelo de Clustering para el gimnasio Model Fitness 
# 🎯Objetivo:
Los clientes representan el pilar fundamental de una empresa, priorizar la retención de clientes estabiliza los ingresos y maximiza el valor a largo plazo, en este proyecto se analizarán los factores de cancelación de los clientes del gimnasio Model Fitness así como anticiparse a los riesgos de abandono mediante un Modelo de Clustering de Machine Learning.
# Preguntas clave:
-	¿Cuáles son las variables que explican que los clientes cancelen la inscripción al gimnasio?
-	¿Cuál es el porcentaje de clientes que abandonan el gimnasio?
-	¿Cuántos tipos de clientes existen en el gimnasio Model Fitness y cuál es su Tasa de cancelación?
<img width="1" height="1" alt="image" src="https://github.com/user-attachments/assets/ff502aab-3b19-4997-8c27-b010954ae2f8" />

---

# 🧠Habilidades y 🛠️Herramientas 
* Programación: Python (pandas, numpy, matplotlib, seaborn, scipy, sklearn)
* Manipulación de datos: Limpieza, transformación y preparación de conjuntos de datos complejos para su análisis
* Análisis de datos: Análisis estadístico y visualización de datos
* Machine Learning: Entrenamiento de modelos de Regresión Logística, Bosque Aleatorio, y se utilizó Clustering para segmentar a los clientes.
<img width="1" height="1" alt="image" src="https://github.com/user-attachments/assets/ff502aab-3b19-4997-8c27-b010954ae2f8" />

---

# 🗂️Metodología

# Preparación de datos: 
*	Se limpiaron los datos y estandarizaron los datos, se observó la ausencia de datos nulos y datos duplicados.

# Análisis Exploratorio de Datos(EDA):
*	Se realizo un análisis estadístico de las variables y se observó la distribución de los datos con histogramas. 
*	Se realizo un query para el grupo de clientes que cancelaron y no cancelaron la inscripción al gimnasio.
*	Se realizo un gráfico de pastel para analizar el porcentaje de clientes que abandonaron el gimnasio.
*	Se aplico la medida estadística de correlación junto un gráfico de calor para observar que variables están correlacionadas y se encontró multicolinealidad entre las variables “avg_class_current_month" y "avg_class_frecuency_total".

# Modelo Predictivo: 
*	Se entrenaron dos modelos de predicción; Regresión Logística y Bosque Aleatorio y se analizaron sus métricas de evaluación como; accuracy, precisión y recall.
*	Se escogió el Modelo de Clustering para agrupar a los clientes y detectar los factores de riesgo de abandono para cada tipo de clientes.
      
<img width="1" height="1" alt="image" src="https://github.com/user-attachments/assets/ff502aab-3b19-4997-8c27-b010954ae2f8" />

---





# 📊Conclusiones:

*	Los principales factores que afectan el abandono del gimnasio en los clientes son: la ubicación, las personas que no están asociada a una empresa, las personas que no entran a clases grupales, la edad entre los 20 a 35 años son los clientes con mayor abandono.
*	El porcentaje de los clientes que abandonan el gymnasio es de 26.5% y el 73.5% se encuentra activo.
*	El Modelo de Clustering segmento 5 tipos de clientes; clientes perdidos o en riesgo, clientes débiles,  clientes promedio,  clientes más activos y clientes valiosos.
<img width="1" height="1" alt="image" src="https://github.com/user-attachments/assets/ff502aab-3b19-4997-8c27-b010954ae2f8" />

---

# 📈Estrategias recomendadas
*	El cluster 2 (clientes perdidos y en riesgo) y el cluster 3 (clientes débiles) tienen una alta tasa de cancelación, para este tipo de clientes se les puede ofrecer un descuento de estudiantes ya que los clientes más jóvenes son lo que suelen cancelar más, se les puede ofrecer una promoción al invitar a un amigo o familiar, invitarlos a tomar clases grupales o tener un horario más amplio para tomar clases grupales en el gimnasio, ya que representa un factor de cancelación para los que no toman clases grupales.

