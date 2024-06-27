## Descripción del proyecto

La compañía móvil Megaline no está satisfecha al ver que muchos de sus clientes utilizan planes heredados. Quieren desarrollar un modelo que pueda analizar el comportamiento de los clientes y recomendar uno de los nuevos planes de Megaline: Smart o Ultra.

Tenemos acceso a los datos de comportamiento de los suscriptores que ya se han cambiado a los planes nuevos. Para esta tarea de clasificación, se debe crear un modelo que escoja el plan correcto. Como los datos ya están procesados, se puede proceder directamente a la creación del modelo.

El objetivo es desarrollar un modelo con la mayor exactitud posible. En este proyecto, el umbral de exactitud es 0.75. Se utilizará el dataset para comprobar la exactitud del modelo.

## Conclusiones

El objetivo principal del proyecto era desarrollar un modelo de clasificación para la compañía móvil Megaline, que pudiera analizar el comportamiento de los clientes y recomendar uno de los nuevos planes: Smart o Ultra. Se tenía acceso a datos de comportamiento de suscriptores que ya habían migrado a los planes nuevos, lo que permitió la creación del modelo de clasificación.

### Análisis de Resultados Específicos

**Árbol de Decisión:** Se observó que profundidades mayores, como 23-28, ofrecían una exactitud perfecta, pero indicaban probable sobreajuste. Se sugirió que una profundidad en el rango de 10 a 15 ofrecía un buen equilibrio entre precisión y capacidad de generalización.

**Regresión Logística:** Los resultados sugirieron que el modelo de regresión logística no alcanzaba el umbral de exactitud deseado. Se identificó la necesidad de ajustar los hiperparámetros del modelo para mejorar su rendimiento.

**Bosque Aleatorio:** Se determinó que el modelo con 17 estimadores ofrecía una buena combinación de exactitud en los conjuntos de validación y prueba, representando un equilibrio entre sesgo y varianza. Se recomendó elegir el modelo con mejor rendimiento en validación y una exactitud aceptable en prueba.

### Prueba de Cordura y Comparación de Modelos con Datos Reales y Aleatorios

En resumen, los resultados demuestran la eficacia del modelo real en la clasificación de datos en comparación con los modelos generados aleatoriamente. La diferencia en la exactitud subraya la importancia del aprendizaje significativo de los datos para la construcción de modelos de clasificación precisos y fiables, lo que refuerza la validez del modelo desarrollado en este proyecto y sugiere su capacidad para generalizar patrones reales en los datos de Megaline.
