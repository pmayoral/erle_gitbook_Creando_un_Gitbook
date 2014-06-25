# Ejercicios y Test

#### Ejercicios

Un libro puede contener ejercicios interactivos (actualmente sólo en Javascript). Un ejercicio es un código proporcionado para el lector, que se da un editor de código para escribir una solución que se comprueba con el código de validación del libro del autor.

Un ejercicio se define en 4 partes:

* Ejercicio **Mensaje**/Objetivos (en markdown/texto)
* **Código inicial** para mostrar al usuario, proporcionando un punto de partida
* **Solución** del código, una solución correcta para el ejercicio
* **Validación** del código que pone a prueba la exactitud de la entrada del usuario

Los ejercicios tienen que empezar y terminar con una barra de separación (``` ---``` o ```***```). Debe contener 3 elementos de código (**base**, **solución** y **validación**). Puede contener un cuarto elemento que proporcione el código de **contexto** (funciones, importaciones de librerias, etc... que no deben ser mostrados al usuario).


    ---

    Define a variable `x` equal to 10.

    ```js
    var x =
    ```

    ```js
    var x = 10;
    ```

    ```js
    assert(x == 10);
    ```

    ```js
    // This is context code available everywhere
    // The user will be able to call magicFunc in his code
    function magicFunc() {
        return 3;
    }
    ```

    ---

#### Cuestionarios

Un libro también puede contener cuestionarios interactivos.

El cuestionario se define de la misma manera que un ejercicio.


    ---

    Here is the introduction for the quiz

    This is Question 1:
    - [x] This is the proposition 1 (the correct one)
    - [ ] This is the proposition 2

    > This is a help message when the answer to question 1 is wrong

    This is Question 2:
    - [ ] This is the proposition 1
    - [x] This is the proposition 2 (correct)
    - [x] This is the proposition 3 (correct)

    > This is a help message when the answer to question 2 is wrong

    ---

