🛢️ Predicción de rentabilidad en pozos petrolíferos – OilyGiant

📌 Propósito del proyecto

Identificar la región óptima para desarrollar 200 nuevos pozos petrolíferos, maximizando el beneficio económico y minimizando el riesgo de pérdida, mediante modelos de regresión lineal y análisis estadístico con bootstrapping.

📝 Descripción

Como analista de datos en OilyGiant, tu tarea consiste en evaluar tres regiones con datos históricos de calidad de crudo y volumen de reservas. El objetivo es construir un modelo predictivo que permita seleccionar los pozos más rentables 
y la región con mayor proyección de beneficios. El análisis considera restricciones presupuestales, métricas de rentabilidad y evaluación de riesgo.

💻 Funcionalidades

📥 Preparación de datos

• 	Carga y verificación de coherencia en los archivos , , .

• 	Exploración inicial de distribución de variables.

📈 Entrenamiento de modelos

• 	Regresión lineal aplicada a cada región.

• 	Predicción del volumen medio de reservas.

• 	Evaluación de precisión mediante RMSE.

💰 Evaluación de rentabilidad

• 	Cálculo del umbral mínimo de rentabilidad por pozo: 111.1 unidades.

• 	Comparación con volumen medio de reservas por región.

• 	Propuesta de estrategias de optimización operativa.

🧮 Cálculo de beneficios

• 	Selección de los 200 pozos con mayores reservas por región.

• 	Estimación de ganancias potenciales en USD.

📊 Análisis de riesgo con bootstrapping

• 	Simulación con 1000 muestras para cada región.

• 	Cálculo de beneficio promedio, intervalo de confianza del 95% y riesgo de pérdida.

🔧 Herramientas utilizadas

• 	Python

• 	Pandas

• 	NumPy

• 	Scikit-learn

• 	Matplotlib

• 	Bootstrapping (estadística)

📊 Resultados

• 	Volumen medio de reservas y RMSE:

• 	Región 0: 92.40 unidades  RMSE: 37.76

• 	Región 1: 68.71 unidades  RMSE: 0.89

• 	Región 2: 94.77 unidades  RMSE: 40.15

• 	Ganancias potenciales (200 pozos):

• 	Región 0: $138,966,584.80

• 	Región 1: $124,869,381.15

• 	Región 2: $133,779,815.14

• 	Bootstrapping – Beneficio promedio y riesgo:

• 	Región 0: $10.39B  Riesgo: 0.00%

• 	Región 1: $7.73B  Riesgo: 0.00%

• 	Región 2: $10.66B  Riesgo: 0.00%

✅ Conclusiones

Aunque inicialmente se seleccionó la Región 0 por su volumen de reservas, el análisis de beneficios con bootstrapping reveló que Región 2 ofrece el mayor beneficio promedio sin riesgo de pérdida. Por tanto, Región 2 es la mejor opción para el desarrollo de pozos petrolíferos si la prioridad es seguridad en la inversión y rentabilidad financiera.

Este proyecto demuestra cómo el análisis de datos puede guiar decisiones estratégicas en el sector energético, combinando modelos predictivos con evaluación económica y de riesgo.
