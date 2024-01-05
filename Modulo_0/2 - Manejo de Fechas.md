# Ejercicio 2 

## Manejo de Fechas.
 
<u>**Crear un nodo libre nuevo llamado MANEJO_FECHAS**</u>

### MANEJO DE FECHAS

1. Definir 2 variables "FECHA1" y "FECHA2", a las mismas debemos crearlas con la funcion "NumbersToDate":

```
//Esta funcion tiene parametros 
    --- obligatorios: anio
    --- opcionales: mes,dia,hora,minuto,segundo;
// ademas, estos parametros deben ser NUMEROS.
numbersToDate(anio, mes,dia,hora,minuto,segundo)    
```

2. Asignale a la variable FECHA1 el valor de: 07/01/2018 y a FECHA2 29/02/2020. Recorda utilizar la funcion numbersToDate.

## Funciones para el manejo de fechas: 

1. Calcula la cantidad de dias de diferencia que hay entre las dos fechas y asignalo en una variable llamada "diferenciaFechasDias". Para ello utiliza la funcion DateDiff().

    ```
    -- parametros obligatorios:
        --variable1, variable2, tipoUnidad
    -- parametros opcionales: 
            --Inicio semana.

    diferenciaFechaDias = DateDiff(variable1, variable2, tipoUnidad*, [inicioSemana])

    Tipo de unidades: 
        M4_YEAR | M4_MONTH | M4_DAY | M4_HOUR | M4_MINUTE | M4_SECOND | M4_WEEK

    inicioSemana: va del 1 al 7, siendo 1 Lunes. Sirve para indicar apartir de que dia contar el inicio de semana.    
    ```

2. Hay funciones mas especificas para resolver la diferencia entre fechas, como por ejemplo "Months()" y "Years()". Utilizalas, las dos funciones reciben los mismos parametros: (variable1, variable2). Luego, hace la diferencia de años y meses con la funcion "DateDiff()" y compara los resultados mostrandolos en pantalla con un setLog.

3. Para cerrar el modulo, utilizaremos las funciones de agregacion y de obtencion.

    ```
     **AGREGACION:** 

    //Ejercicio a:
    Agregarle dos meses a la fecha 1
    variable: agregoDosMeses
    función: AddMonths(fecha, cantMesesParaSumar)

    //Ejercicio b:
    Agregarle tres años a la fecha 1
    Crear y asignar a la variable: agregoTresAnios
    función a utilizar: AddYears(fecha, cantAniosParaSumar)

    //ejercicio c:
    Restarle un mes a la fecha 2
    Crear y asignar a la variable: restoUnMes
    función a utilizar: AddMonths(fecha, cantMesesParaSumar)

    ```

    ```
    **OBTENCION:**

    -- Para este ejercicio deberas consultar la guia de desarrollo del lenguaje LN4 el cual te servirá para el siguiente modulo. El mismo esta disponible en esta misma carpeta.

    //Ejercicio a    
    Obtener la cantidad de días del mes de la fecha 2
    variable: cantidadDiasMes
    función: DaysOfMonth()
    
    //Ejercicio b
    Obtener el día de la fecha 1
    variable: diaFecha
    funcion: DxDay()

    //Ejercicio c   
    Obtener el mes de la fecha 1
    variable: mesFecha
    funcion: DxMonth()
    
    //Ejercicio d
    Obtener el año de la fecha 1
    variable: anioFecha
    funcion: DxYear()
    
    ```

