# analisis_food-store
## 📊 Análisis para Tienda de Alimentos
En este proyecto se realiza un estudio del comportamiento de los usuarios dentro de la aplicación de una empresa de venta de alimentos.
El análisis incluye una exploración de los datos, la elaboración de un embudo de conversión y la evaluación de un experimento A/A/B para validar el impacto de una variante en el comportamiento de los usuarios.

## 🎯 Objetivos

* Análisis de embudo:
  * Calcular la proporción de usuarios en cada evento.
  * Evaluar la proporción de usuarios que avanzan entre etapas.
  * Analizar las etapas críticas del recorrido.
  * Determinar cuántos usuarios completan el viaje completo (del primer evento hasta el pago).

* Análisis del experimento A/A/B:
  * Calcular el número de usuarios por grupo.
  * Evaluar las diferencias entre los grupos de control (A/A).
  * Comparar los eventos entre los grupos de control.
  * Analizar la diferencia entre los grupos de control y el grupo con variante.

## 📅 Periodo Analizado
El experimento abarcó del 01/08/2019 al 07/08/2019 (7 días).

## 📈 Hallazgos Clave

* Los eventos “CartScreenAppear” y “PaymentScreenSuccessful” muestran proporciones de usuarios muy similares, lo que indica que quienes agregan productos al carrito finalizan el pago.
* En el recorrido del usuario (MainScreenAppear → OffersScreenAppear → CartScreenAppear → PaymentScreenSuccessful), la mayor pérdida ocurre en la etapa de pago, alcanzando solo al 6.1% de los usuarios iniciales.
* No se encontraron diferencias entre los grupos de control y el grupo variante (248), por lo que el cambio en la fuente no parece afectar la actividad de los usuarios.

## 🔍 Conclusiones Estratégicas
El comportamiento de los usuarios a lo largo del embudo es estable, sin evidencia de sesgos experimentales.
La similitud entre grupos sugiere que las modificaciones introducidas no alteran la interacción de los usuarios, permitiendo enfocar futuros esfuerzos en la optimización del proceso de pago.

## 🧪 Herramientas y Tecnología
* Python
* Pandas
* NumPy
* Matplotlib / Seaborn / Plotly
* SciPy
* Statsmodels
* Jupyter Notebook
