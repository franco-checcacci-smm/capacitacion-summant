# Ejercicio 1 

## Sentencias de repeticion.
 
<u>**Crear un nodo libre nuevo llamado CAR_SENTENCIAS_REPETICION**</u>

### Sentencia "DO"

0. Creamos un metodo llamado "CAR_SENTENCIA_DO".

1. Definimos una variable llamada iterador y le asignamos el valor 0. 

2. En esta ocasion utilizaremos la sentencia Do para sumarle 1 al iterador hasta que llegue al numero 5.

3. Por cada pasada imprimir con un SETLOG el valor del iterador y concatenarle un texto. Sintaxis de la sentencia DO:

    ```
    DO 
        proceso()
    UNTIL condicion
    ```

**Para concatenenar un texto al SETLOG no olvides convertir la variable iterador a STRING:**

    TOSTRING(variable, 0) //el 0 es la precision, cuantos decimales vamos a mostrar.

### Sentencia "WHILE"

0. Creamos un metodo llamado "CAR_SENTENCIA_WHILE".

1. Definimos una variable llamada iterador y le asignamos el valor 0. 

2. En esta ocasion utilizaremos la sentencia WHILE para sumarle 1 al iterador hasta que llegue al numero 5.

3. Por cada pasada imprimir con un SETLOG el valor del iterador y concatenarle un texto. Sintaxis de la sentencia WHILE:

    ```
    WHILE condicion 
        proceso()
    WEND
    ```


### Sentencia "FOR"

0. Creamos un metodo llamado "CAR_SENTENCIA_FOR".

1. Definimos una variable llamada iterador y le asignamos el valor 0. 

2. En esta ocasion utilizaremos la sentencia FOR para sumarle 1 al iterador hasta que llegue al numero 5.

3. Por cada pasada imprimir con un SETLOG el valor del iterador y concatenarle un texto. Sintaxis de la sentencia FOR:

    ```
    // Solemos usar N como variable iteradora.
    // VARIABLE_TOPE: hasta donde va a recorrer.
    // Se puede declarar la variable en el mismo for:
    FOR N=0 TO VARIABLE_TOPE  
        proceso()
    NEXT
    ```
