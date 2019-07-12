Comportamiento dinamico del sistema
=================================

Especificacion de escenarios
--------------------------

.. image:: images2/casosdeuso.png
    :scale: 70 %
    :align: center

Descripción casos de uso
--------------------------
Definición de Actores.
ACT - <01>
Usuario ejecutivo web
Descripción
Corresponde al usuario que accede al sistema desde un navegador web 

ACT - <02>
Usuario ejecutivo movil
Descripción
Corresponde al usuario que accede al sistema a través de un su dispositivo móvil

ACT - <03>
Administrador
Descripción
Corresponde al usuario que accede desde la web para filtrar las preguntas y las respuestas de los usuarios mobil y usuarios web respectivamente

















CU - <01>
Desplegar gráfica de datos de parámetros medioambientales.
Actores
ACT - <01>
Descripción
Permite al usuario desplegar un gráfico de parámetros medioambientales de temperatura y humedad en un intervalo de tiempo
Secuencia Normal
Paso
Acción
1
El usuario selecciona un intervalo de tiempo
2
El sistema extrae los datos de la base de datos
3
Se despliega la gráfica de temperatura y humedad v/s tiempo.
Secuencia Alternativa
Paso
Acción
 
1b
Se notifica al usuario que los parámetros de búsqueda fueron ingresados incorrectamente














CU - <02>
Responder preguntas medioambientales
Actores
ACT - <01>
Descripción
Permite al usuario web responder una pregunta de un usuario móvil
Pre-condición
Hay preguntas por responder
Secuencia Normal
Paso
Acción
1
Se despliegan preguntas contestadas y no contestadas
2
Se selecciona una pregunta
3
Se envía una respuesta y queda a la espera de ser validada por el administrador
Secuencia Alternativa
Paso
Acción
 
3.1
Se notifica al usuario que la respuesta no cumple con cantidad de caracteres mínimos












CU - <03>
Desplegar gestión de preguntas
Actores
ACT - <03>
Descripción
Permite al usuario administrador desplegar una pagina de administracion de preguntas y respuestas
Pre-condición
Estar autenticado como administrador
Secuencia Normal
Paso
Acción
1
Se despliega página de gestión de preguntadas
2
El usuario selecciona una pregunta
3
Se despliega pregunta seleccionada con sus respectivas respuestas






















CU - <04>
Permitir publicar pregunta
Actores
ACT - <03>
Descripción
Permite al usuario administrador validar o eliminar una pregunta o respuesta que pueda ser ofensiva
Pre-condición
1.-Estar autenticado como administrador
2.-Haber seleccionado una pregunta/respuesta
Secuencia Normal
Paso
Acción
1
Se despliega pregunta/respuesta
2
Se valida pregunta/respuesta
3
Se publica en el foro





















CU - <05>
Desplegar gestión de usuarios
Actores
ACT - <03>
Descripción
Permite al usuario poder listar los usuarios como también eliminar
Pre-condición
Estar autenticado como administrador
Secuencia Normal
Paso
Acción
1
Se despliega listado de usuarios
Secuencia Alternativa
Paso
Acción
 
1.1
Se elimina un usuario


1.2
Se actualiza listado de usuario






















CU - <06>
Realizar pregunta medioambiental
Actores
ACT - <02>
Descripción
Permite al usuario poder realizar una pregunta medioambiental
Pre-condición
Estar autenticado como administrador
Secuencia Normal
Paso
Acción
1
Desplegar formulario de pregunta


2
Enviar pregunta al sistema para ser validada
Secuencia Alternativa
Paso
Acción
 
1.1
La pregunta no cumple con requisitos de caracteres mínimos




















CU - <07>
Desplegar gráfica de datos de parámetros medioambientales.
Actores
ACT - <02>
Descripción
Permite al usuario poder realizar una pregunta medioambiental
Pre-condición
Estar autenticado como administrador
Secuencia Normal
Paso
Acción
1
Mostrar menú de selección de preguntas respondidas, no respondidas y todas las preguntas.


2
Se selecciona un parámetro del punto 1


3
Se despliega listado según el parámetro seleccionado















CU - <08>
Desplegar lista de todas las preguntas realizadas
Actores
ACT - <01>
Descripción
Permite al usuario desplegar un gráfico de parámetros medioambientales de temperatura y humedad en un intervalo de tiempo
Secuencia Normal
Paso
Acción
1
El usuario selecciona un intervalo de tiempo
2
El sistema extrae los datos de la base de datos
3
Se despliega la gráfica de temperatura y humedad v/s tiempo.
Secuencia Alternativa
Paso
Acción


1b
Se notifica al usuario que los parámetros de búsqueda fueron ingresados incorrectamente

