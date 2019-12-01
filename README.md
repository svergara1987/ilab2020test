# Test de Programación

Bienvenido al test de programación para candidatos del **IBM Innovation Lab 2020**. 

El test consta de 4 pruebas que podrán ser resueltas utilizando alguno de los siguientes lenguajes de programación: 
- Java
- Javascript / Node.js
- Python
- Go
- .Net Core

Al finalizar el test, se deberá dejar todo el código subido a un repositorio de github (http://github.com) privado en tu cuenta personal cuya estructura será la siguiente

```
NOMBRE_DEL_REPO_PRIVADO
  |-- Ejercicio 1
          |-- código del ejercicio 1
  |-- Ejercicio 2
          |-- código del ejercicio 2
  |-- Ejercicio 3
          |-- código del ejercicio 3
  |-- Ejercicio 4
          |-- código del ejercicio 4
```
Agregar como colaborador al repositorio al usuario `svergara1987`

## Ejercicio 1

Codificar la función `factorial (num)` para que tome el parámetro `num` que se pasa y devuelva el factorial del mismo.

Por ejemplo: si num = 4, entonces tu programa debería devolver (4 * 3 * 2 * 1) = 24.

La entrada siempre será un número entero.

Ejemplos:
- Entrada: 3 => Salida: 6
- Entrada: 4 => Salida: 24
- Entrada: 8 => Salida: 40320

Tiempo estimado de resolución: < 20 min

## Ejercicio 2

Desarrollar la función `reverso (str)` para que dado el parametro `str`de tipo `String` devuelva la cadena de caracteres en orden inverso. 

Por ejemplo: si la cadena de entrada es "Hola Mundo", entonces su programa debería devolver la cadena "odnuM aloH".

Ejemplos
- Entrada: "chorizo" => Salida: "ozirohc"
- Entrada: "I Love Code" => Salida: "edoC evoL I"

Tiempo estimado de resolución: < 20 min

## Ejercicio 3

Desarrollar la función `numeroPentagonal (num)` para que dado el parámetro `num`(entero positivo), determine cuántos puntos existen en una forma pentagonal alrededor de un punto central en la iteración número `num`. 

Por ejemplo, en la imagen a continuación puede ver que en la primera iteración solo hay un punto, en la segunda iteración hay 6 puntos, en la tercera hay 16 puntos y en la cuarta hay 31 puntos.

![numeroPentagonal](https://github.com/svergara1987/ilab2020test/blob/master/img/pentagonalNumber.png)

Tiempo estimado de resolución: < 30 min

## Ejercicio 4

Luego de la introducción a Watson Assistant, el objetivo de este último ejercicio es crear una aplicación que se integra con un asistente virtual desplegado en la nube utilizando Watson Assistant. 

El asistente virtual deberá ser capaz de responder las siguientes preguntas (que podrán venir presentadas de diversas formas):
1. color favorito?
2. sos hombre o mujer? / cual es tu sexo?
3. que es lo que te atrae de trabajar en IBM? / por qué IBM?
4. qué te gustaría hacer en el futuro?
5. saludos de apertura de conversación
6. saludos de cierre de conversación
7. responder ante insultos o agravios
8. responder a la pregunta de que dia es hoy
9. responder a la pregunta que hora es (GMT-3 Montevideo)
10. nombre completo?

Las respuestas a las preguntas anteriores **DEBEN** ser personales, tal cual si las estuvieses respondiendo vos. 

Adicional a responder las preguntas anteriores, el asistente deberá ser capaz de llevar adelante el siguiente flujo de conversación, donde U representa a un usuario final y WA al asistente virtual:
- U: quiero aprender a programar
- WA: te puedo enseñar de los siguientes lenguajes, Java, Python o Go. Cual de los 3 queres aprender?
- U: Python / el segundo / 2
- WA: Perfecto, te enseño de Python entonces

La aplicación de escritorio recibe 2 parámetros de tipo string al momento de su ejecución. 
La lógica de la aplicación deberá hacer un llamado al assistente virtual utilizando el primer parámetro, y luego de obtener una respuesta del asistente, mantener una conversación respondiendo con el segundo parámetro. 

Ejemplo de interacción aplicación (A) con el asistente virtual (WA):
- A: param1
- WA: respuesta a invocación con param1
- A: param2
- WA: respuesta a invocación con param2

Si param1 = "enseñame de programación" y param2 = "el primero", entonces la conversación se transformaría en:
- A: enseñame de programación
- WA: te puedo enseñar de los siguientes lenguajes, Java, Python o Go. Cual de los 3 queres aprender?
- A: el primero
- WA: Perfecto, te enseño de Java entonces

Links de interes para este ejercicio:
- Watson Assistant Getting Started: https://cloud.ibm.com/docs/services/assistant?topic=assistant-getting-started
- Watson Assistant API Reference: https://cloud.ibm.com/apidocs/assistant/assistant-v2

Tiempo estimado de resolución: 120 min