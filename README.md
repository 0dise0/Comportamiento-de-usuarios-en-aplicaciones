# Descripción
Trabajas en una empresa emergente que vende productos alimenticios. Debes investigar el comportamiento del usuario para la aplicación de la empresa.

## Preguntas importantes
Primero, estudia el embudo de ventas. Descubre cómo los usuarios y las usuarias llegan a la etapa de compra. ¿Cuántos usuarios o usuarias realmente llegan a esta etapa? ¿Cuántos se atascan en etapas anteriores? ¿Qué etapas en particular?

Luego, observa los resultados de un test A/A/B. (Sigue leyendo para obtener más información sobre los test A/A/B). Al equipo de diseño le gustaría cambiar las fuentes de toda la aplicación, pero la gerencia teme que los usuarios y las usuarias piensen que el nuevo diseño es intimidante. Por ello, deciden tomar una decisión basada en los resultados de un test A/A/B.

Los usuarios se dividen en tres grupos: dos grupos de control obtienen las fuentes antiguas y un grupo de prueba obtiene las nuevas. Descubre qué conjunto de fuentes produce mejores resultados.

Crear dos grupos A tiene ciertas ventajas. Podemos establecer el principio de que solo confiaremos en la exactitud de nuestras pruebas cuando los dos grupos de control sean similares. Si hay diferencias significativas entre los grupos A, esto puede ayudarnos a descubrir factores que pueden estar distorsionando los resultados. La comparación de grupos de control también nos dice cuánto tiempo y datos necesitaremos cuando realicemos más tests.

Utilizarás el mismo dataset para el análisis general y para el análisis A/A/B. En proyectos reales, los experimentos se llevan a cabo constantemente. El equipo de análisis estudia la calidad de una aplicación utilizando datos generales, sin prestar atención a si los usuarios y las usuarias participan en experimentos.

## Descripción de los datos

Cada entrada de registro es una acción de usuario o un evento.

EventName: nombre del evento.
DeviceIDHash: identificador de usuario unívoco.
EventTimestamp: hora del evento.
ExpId: número de experimento: 246 y 247 son los grupos de control, 248 es el grupo de prueba.


## Objetivo
Nuestro objetivo principal consiste en aumentar las ventas de nuestra empresa que vende productos alimenticios. 

## Metodología
Esto lo podremos lograr al analizar los datos que obtuvimos de la realización de un test A/A/B que consiste en comprobar si los cambios realizados en la aplicación pueden mejorar las ventas. Analizando nuestros datos podremos llegar a concluir si los cambios tuvieron una relevancia o no en las ventas, por lo que debemos explorar nuestros datos y limpiarlos de posibles errores que puedan comprometer nuestro análisis.

## Conclución general
Nuestro objetivo principal consistió en aumentar las ventas para nuestra empresa que vende productos alimenticios, una de las formas para realizar esto fue realizar un test A/A/B para comparar los cambios realizados en la aplicación donde se realizan las compras, de esta forma podremos comprobar si los cambios realizados tuvieron un valor significativo en las ventas o si los cambios realizados no afectaron positivamente en estas.
Una vez que agrupamos a los usuarios para cada evento en nuestros datos, estudiamos el embudo de eventos por los que los usuarios pasaron para realizar una compra exitosa, de igual forma calculamos el porcentaje de conversión y la tasa de pérdida de usuarios para cada evento en su secuencia, como pudimos observar en la etapa de pantalla principal a la de ofertas es donde perdemos más usuarios con un 38% de pérdida, del 100% de los usuarios solo el 48% completa una compra exitosa.
