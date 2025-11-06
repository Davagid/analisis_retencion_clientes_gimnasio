# Análisis de retención de clientes — Model Fitness

## Descripción
Análisis de datos para predecir y comprender la pérdida de clientes en la cadena de gimnasios **Model Fitness**.  
El objetivo fue identificar patrones de comportamiento, segmentar perfiles de usuarios y proponer estrategias efectivas de retención basadas en datos.

## Objetivos
- Predecir la probabilidad de cancelación de clientes (`Churn`).
- Identificar los factores más relevantes asociados a la pérdida.
- Crear clústeres de clientes con comportamientos similares.
- Formular recomendaciones accionables para mejorar la retención.

## Tecnologías y librerías
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn, scipy)
- Jupyter Notebook (análisis reproducible)

> Nota: las versiones y dependencias exactas se encuentran en: `requirements.txt`.

## Conclusiones
- Se identificaron **5 perfiles de clientes** con patrones de uso distintos.  
- Las variables **`Lifetime`**, **`Avg_class_frequency_current_month`** y **`Contract_period`** fueron las más influyentes en la cancelación.  
- La **regresión logística** alcanzó un **92% de exactitud** y permitió detectar los grupos más propensos al abandono.  
- Se propusieron estrategias de **retención personalizada**, con potencial para reducir la tasa de cancelación general en un **15–20%**.

## Instrucciones de uso
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/analisis_retencion_clientes_gimnasio.git

   cd analisis_retencion_clientes_gimnasio

2. Instalar las dependencias:

pip install -r requirements.txt

3. Abrir el notebook principal:

notebooks/analisis_retencion_clientes.ipynb

4. Ejecutar las celdas para reproducir el análisis.
