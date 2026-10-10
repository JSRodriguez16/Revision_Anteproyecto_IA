## Integrantes
- Juan Sebastián Rodríguez Carreño — 20231020107
- Santiago Zamudio Díaz — 20231020128
- Felipe Cárdenas Mora — 20231020145

## Formulación del problema
Las enfermedades cardiovasculares (ECV) representan la principal causa de muerte a nivel mundial. Según la Organización Mundial de la Salud (OMS), se estima que en 2022 alrededor de 19,8 millones de personas fallecieron por ECV, lo que equivale aproximadamente al 32 % de todas las muertes globales, estando una gran parte de estas derivadas de infartos y eventos arrítmicos. A pesar de estas altas cifras de mortalidad, el abordaje clínico actual suele estar enfocado en la detección diagnóstica cuando la sintomatología ya es severa, limitando la ventana de tiempo para actuar. La detección temprana se ve obstaculizada por la alta dimensionalidad y complejidad técnica de los datos electrocardiográficos (ECG), lo que hace que aislar características o patrones sutiles de riesgo previos a un evento fatal sea una tarea que supera el análisis clínico humano convencional. En consecuencia, existe una necesidad latente de implementar técnicas de aprendizaje automático que simplifiquen estas características de alta dimensionalidad para clasificar de manera automatizada y oportuna las señales de arritmia.

## Pregunta de investigación
¿Cómo puede el análisis retrospectivo de información electrocardiográfica y clínica, proveniente del conjunto de datos abiertos PhysioNet MIT-BIH Arrhythmia Database, contribuir a la clasificación de señales de arritmia mediante técnicas de reducción de dimensionalidad y aprendizaje automático?

## Hipótesis
El modelo resultante logrará una exactitud (*accuracy*) mínima del 80 % en la clasificación de señales de arritmia, considerando este porcentaje como el valor umbral esperado para demostrar la capacidad del algoritmo al manejar variables biomédicas de alta dimensionalidad.

## Objetivo general
Construir y evaluar el desempeño de un modelo basado en técnicas de reducción de dimensionalidad y aprendizaje automático para clasificar señales de arritmia, con el fin de contrastar su desempeño y alcanzar una exactitud mínima del 80 %.

## Objetivos específicos
1. Extraer y preprocesar las características de las señales electrocardiográficas que influyen con mayor peso en la clasificación del modelo.
2. Aplicar la técnica de reducción de dimensionalidad PCA en el conjunto de datos clínicos para seleccionar los componentes principales y reducir el riesgo de sobreajuste (*overfitting*) en los modelos, optimizando así su desempeño.
3. Evaluar diversos modelos de aprendizaje supervisado comparando sus métricas de desempeño (tales como exactitud, sensibilidad y especificidad) para categorizar y seleccionar el clasificador definitivo que constituirá el planteamiento de solución.

## Justificación
El presente proyecto de investigación computacional tiene como finalidad optimizar las herramientas analíticas para la clasificación de señales de arritmia. Una clasificación precisa podría aportar información al personal de salud para orientar intervenciones terapéuticas o preventivas; sin embargo, este proyecto no evalúa su efecto en la reducción de la mortalidad por fallas cardíacas.

El valor teórico y metodológico de este proyecto radica en evaluar rigurosamente cómo el uso de algoritmos específicos de reducción de dimensionalidad (como PCA) permite mitigar el problema de los espacios de alta dimensionalidad al procesar series de tiempo clínicas complejas (señales ECG). Con esto, se aporta un marco de trabajo de ingeniería útil para futuras implementaciones de *machine learning* en medicina.

La viabilidad del proyecto está respaldada debido a la disponibilidad en modalidad de acceso abierto de conjuntos de datos estandarizados globales, como la base de datos PhysioNet MIT-BIH. Al ejecutarse el modelado de forma puramente computacional y retrospectiva sobre este *dataset*, el análisis no depende de ensayos de tamizaje poblacional directo ni infraestructura hospitalaria física, acotando de forma segura su alcance analítico.

## Revisión de coherencia

- La pregunta surge de la problemática en mortalidad a raíz de arritmias a nivel mundial.
- La hipótesis plantea un umbral de exactitud para la clasificación de señales, pero el proyecto no evalúa mejoras en la calidad de vida de los pacientes.
- El objetivo general plantea la construcción y evaluación de un modelo de clasificación mediante técnicas de reducción de dimensionalidad y aprendizaje automático.
- Los objetivos específicos contribuyen al objetivo general mediante la extracción y el preprocesamiento de características, la reducción de dimensionalidad y la comparación de modelos con métricas de desempeño.
- La justificación expone la posible utilidad del proyecto ante un problema de salud mundial, aunque sus resultados no demuestran por sí solos un beneficio clínico.
