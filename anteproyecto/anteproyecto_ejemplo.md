# Control predictivo y observador de estados basados en el operador de Koopman: validación en una
suspensión activa vehicular no lineal tipo Quarter-Car
## Formulación del problema
La suspensión de un vehiculo es uno de los sistemas fundamentales para garantisar la estabilidad y la
seguridad durante la conducción, ya que determina cómo interactúa el vehículo con las irregularidades de la
vía. Se estima que más del 60 % de los accidentes de tránsito en Colombia están relacionados con fallas en el
sistema de suspensión, lo que evidencia la urgencia de mejorar estos sistemas en todo los vehículos que
circulan en el país.
Las suspensiones activas permiten modificar de manera controlada las fuerzas ejercidas sobre el sistema
mediante actuadores, lo que les da mayor capacidad de adaptación frente a diferentes condiciones de
operacion que las suspensiones pasivas y semiactivas. Sin embargo, el diseño de estrategias de control para
estos sistemas representa un desafío debido a la naturaleza dinámica y no lineal del modelo físico de la
suspensión.
El Control Predictivo Basado en Modelo (MPC) es actualmente el mejor método de control que existe, porque
predice el comportamiento futuro del sistema y calcula las acciones de control optimizando una función objetivo.
Es ampliamente conocido que un MPCs con modelo no lineal no puede ejecutarse en tiempo real, mientras que
los modelos linealizados pierden precisión cuando el sístema opera lejos del punto de equilibrio.
Sin embargo, el operador de Koopman resuelve este problema, ya que permite representar la dinámica no
lineal de forma lineal en un espacio de mayor dimensión.
No obstante, la incorporación de una representación de mayor dimensión no garantiza por sí misma una mejora
en el desempeño del controlador.
Por esta razón, se requiere desarrollar un controlador MPC basado en el operador de Koopman junto con un
observado de estados, e implementarlo en un vehículo de carga pesada de la flota de la universidad.
Finalmente, se plantea la necesidad de contar con una simulación animada que permita visualizar el
comportamientos de la suspensión, así como una aplicacion movil que informe al conductr sobre el estado de la
vía en tiempo real.
En consecuencia, el problema de investigación consiste en establecer si el operador de Koopman permite
obtener un desempeño adecuado y favorable en el control de la suspensión.
## Pregunta de investigación
¿Cómo se puede mejorar el control de las suspensiones activas mediante técnicas de inteligencia artificial?
## Hipótesis
El controlador MPC basado en el operador de Koopman será el mejor controlador posible y eliminará por
completo las vibraciones transmitidas a los pasajeros.
## Objetivo general
10
Estudiar la aplicacion del operador de koopman en el control predictivo de una suspensión activa tipo QuarterCar.
## Objetivos específicos
1. Conocer los fundamentos teóricos del operador de Koopman y del control predictivo.
2. Obtener un modelo nolineal y un modelo linealisado de la suspensión activa tipo Quarter-Car.
3. Diseñar un controlador MPC basado en el operador de Koopman para la suspensión.
4. Implementar el controlador en un vehículo de carga pesada y validarlo en carretera.
5. Desarrollar una aplicación móvil que informe al conductor sobre el estado de la vía.
## Justificación
Este proyecto es muy importante porque la inteligencia artificial es el futuro de la ingeniería y todos los
ingenieros deberían dominarla.
El proyecto beneficiará a millones de conductores en el país y reducirá los accidentes de tránsito. Además,
cumple con los criterios de conveniencia, relevancia social, valor teórico y viabilidad.