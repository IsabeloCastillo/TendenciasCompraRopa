# TendenciasCompraRopa
Modelo de Machine Learning creado por Isabelo Castillo en prácticas del curso de Inteligencia Artificial.

![Texto Alternativo](imagen_portada.png)

## Contenido General
**Introducción y Objetivos:** El proyecto se centra en analizar las tendencias de compra de los clientes utilizando un conjunto de datos extenso. Se establecen siete objetivos principales, incluyendo clasificación, correlación, conversión, completado, corrección, creación, y modelado.

**Importación de Librerías y Preparación de Datos:** Se importan librerías esenciales para el análisis de datos, visualización, y modelado. El notebook también incluye pasos para cargar y visualizar los datos iniciales.

**Detalles Técnicos**
**Librerías Utilizadas:** Pandas para el manejo de datos, y otras librerías que probablemente se usen para visualización y análisis estadístico.
Datos Iniciales: La primera visualización de datos muestra un DataFrame con información de clientes, incluyendo ID, edad, género, artículo comprado, categoría, cantidad de compra, ubicación, tamaño, color, temporada, calificación de reseña, estado de suscripción, tipo de envío, descuentos aplicados, uso de código promocional, compras previas, método de pago, y frecuencia de compras.

# Estudio sobre las tendencias de compra de clientes

## Definición de preguntas y problemas

Vamos a estudiar las tendencias de compra de los clientes, tendremos un gran conjunto de datos y con ellos trataremos de averiguar muchismos datos relacionados con las compras.

## Objetivos del proyecto

El flujo de trabajo de este __proyecto de ciencia de datos__ resuelve __siete objetivos__ principales.

* __Clasificación.__ Es posible que deseemos clasificar o categorizar nuestras muestras. También es posible que deseemos comprender las implicaciones o la correlación de diferentes clases con nuestro objetivo.


* __Correlación.__ Se puede abordar el problema en función de las características disponibles dentro del conjunto de datos de entrenamiento. ¿Qué características dentro del conjunto de datos contribuyen significativamente a nuestro objetivo de solución? Hablando estadísticamente, ¿existe una correlación entre una característica y el objetivo de la solución? A medida que cambian los valores de las funciones, ¿cambia también el estado de la solución y viceversa? Esto se puede probar tanto para características numéricas como categóricas en el conjunto de datos dado. También es posible que deseemos determinar la correlación entre características distintas de la supervivencia para los objetivos posteriores y las etapas del flujo de trabajo. Correlacionar ciertas características puede ayudar a crear, completar o corregir características.


* __Conversión.__ Para la etapa de modelado, es necesario preparar los datos. Dependiendo de la elección del modelo de algoritmo, se puede requerir que todas las características se conviertan a valores numéricos equivalentes. Por ejemplo, convertir valores categóricos de texto en valores numéricos.


* __Completado.__ La preparación de datos también puede requerir que estimemos los valores faltantes dentro de una característica. Los algoritmos de modelado pueden funcionar mejor cuando no faltan valores.


* __Corrección.__ También podemos analizar el conjunto de datos de entrenamiento dado en busca de errores o posibles valores inexactos dentro de las características e intentar corregir estos valores o excluir las muestras que contienen los errores. Una forma de hacerlo es detectar cualquier valor atípico entre nuestras muestras o características. También podemos descartar completamente una característica si no contribuye al análisis o puede sesgar significativamente los resultados.


* __Creación.__ ¿Podemos crear nuevas características basadas en una característica existente o un conjunto de características, de modo que la nueva característica siga los objetivos de correlación, conversión e integridad?


* __Gráficos.__ Cómo seleccionar los gráficos y diagramas de visualización correctos según la naturaleza de los datos y los objetivos de la solución.
