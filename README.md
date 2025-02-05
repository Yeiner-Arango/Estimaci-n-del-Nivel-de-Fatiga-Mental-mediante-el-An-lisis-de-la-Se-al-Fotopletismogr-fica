# 📌 Estimación del Nivel de Fatiga Mental mediante el Análisis de la Señal Fotopletismográfica

📖 Descripción del Proyecto
Este proyecto busca desarrollar un método objetivo para estimar el nivel de fatiga mental mediante el análisis de la señal fotopletismográfica (PPG). Se busca mejorar los métodos tradicionales basados en cuestionarios mediante señales biológicas que permitan la detección temprana de la fatiga mental.

🎯 Características Principales
•	 Método no invasivo basado en fotopletismografía (PPG).
•	Procesamiento avanzado de señales mediante filtrado y extracción de características relevantes.
•	Modelos de aprendizaje supervisado para estimación del nivel de fatiga.
•	Comparación con métodos tradicionales como cuestionarios MBI.

📂 DATOS DEL ESTUDIO
•	Participantes: 50 trabajadores de oficina (50% hombres, 50% mujeres).
•	Dispositivo utilizado: Sensor MAX30102.
•	Protocolo: Registro de señales PPG + Cuestionario de fatiga mental.
•	Características extraídas: Intervalo entre pulsos, ancho de pulso, amplitud de onda, variabilidad de la frecuencia cardíaca, entre otras.

⚙️ METODOLOGIA
1.	Adquisición de Datos: Registro de señales PPG en condiciones controladas.
2.	Procesamiento de Señales: Filtrado y normalización de la señal.
3.	Extracción de Características: Análisis de la morfología de la señal y parámetros fisiológicos.
4.	Modelado: Implementación de modelos de regresión lineal y gaussianos.
5.	Validación: Evaluación del rendimiento de los modelos con métricas como RMSE, MSE y R-Squared.
   
📊 RESULTADOS
🏆 Mejor modelo: Regresión Gaussiana Rational Quadratic GPR
•	📊 R-Squared: 0.971
•	📉 RMSE: 1.047
