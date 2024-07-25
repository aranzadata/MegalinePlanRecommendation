# Megaline_plan

Se evaluaron las presiciones de tres modelos: Regresión Logística, Árbol de Decisión y Bosque de Decisión para la recomendación de dos planes de la compañía Megaline.

El modelo de regresión logística tuvo la exactitud más baja, con una exactitud de 0.707.

La exactitud promedio de los modelos de árbol de decisión en el conjunto de validación es de 0.778, con una exactitud mínima de 0.754 y una máxima de 0.785.

El mejor modelo de bosque tiene 40 estimadores, 8 niveles de profundidad, con una exactitud en el conjunto de validación de 0.809.

Por lo anterior el modelo final se establece como un bosque de decisión con 40 estimadores y 8 niveles. Estos valores de hiperparámetros ofrecen una exactitud superior al 0.75, con un poder computacional relativamente bajo.

La exactitud del modelo final en el conjunto de prueba es 0.796.
