# Ejercicio 0 
## Estructuras de control 

1. Crear un Meta4Object llamado: tusIniciales_PRACTICA

2. Creamos un nodo llamado CAR_EJECUTA_IF
-- insertar imagen

3. Creamos un metodo llamado "CAR_EJECUTA_IF" con el siguiente boton:
-- insertar imagen

4. Agregamos dos variables (LN4 es un lenguaje debilmente tipificado, esto quiere decir que no requiere declarar el tipo de variable):

    ```
    PRIMER_NUMERO = 10
    SEGUNDO_NUMERO = 15
    ```

5. Crear una sentencia IF, la cual determinará si la variable PRIMER_NUMERO es mayor a SEGUNDO_NUMERO. A continuación demostramos el uso de la sentencia IF:

    ```
    IF condicion THEN 
        proceso()
    ENDIF
    ```
#### Hint: Operadores logicos en LN4:

    ```
     ### Operadores logicos: ### 
        =  | Es igual que...
        <> | Es distinto que... 
        >= | Es mayor igual que..
        <= | Es menor igual que..
        <  | Es menor que...
        >  | Es mayor que...

    ### Bonus ###

    ISNULL(variable) = m4_true | Si la variable es nula... 

    ```

6. Si es mayor debemos mostrar por pantalla (con un SETLOG) el texto "La variable PRIMER_NUMERO es mayor a la variable SEGUNDO_NUMERO". Tipos de setlog:

    ```
    // El primer numero indica que tipo de setlog es.
    
    // -- si queremos mostrar que el resultado fue correcto:
    SETLOG(0,80,80,80, "AQUI VA TU TEXTO")
    
    // -- si queremos indicar que el resultado fue erroneo:
    SETLOG(-1,80,80,80, "AQUI VA TU TEXTO")
    ```

7. Si no es mayor indica con un SETLOG de error el texto: "La variable PRIMER_NUMERO no es mayor a la variable SEGUNDO_NUMERO". Sentencia if else en LN4:

    ```
    IF condicion THEN 
        proceso()
    'si queremos agregar una condicion al else debemos usar 'ELSEIF
    ELSE
        proceso_else()
    ENDIF
    ```

9. Asignarle a las variables PRIMER_NUMERO y SEGUNDO_NUMERO el valor 15.

10. Debemos crear una sentencia que indique el caso en el que las variables sean iguales. Recorda la estructura del IF:

    ```
    IF condicion THEN 
        proceso()
    ELSEIF condicion_2 THEN
        proceso_elseif()
    ELSE
        proceso_else()
    ENDIF

    ```

