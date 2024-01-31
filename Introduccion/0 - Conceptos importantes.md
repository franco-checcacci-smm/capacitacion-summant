# Conceptos importantes.

## En esta sección explicaremos conceptos claves para entender los Meta4Objects.

**Para empezar, explicaremos que es y para que sirve un Meta4Object:**

Un Meta4Object es un componente cuya estructura determina:

- Los datos que se van a extraer de la base de datos
- Las operaciones que se pueden realizar con esos datos
- Un Meta4Object puede estar formado por uno o más nodos. Cada nodo se diseña sobre una estructura. La estructura de un nodo especifica:
    - De qué tablas se quieren extraer datos.
    - De qué columnas de las tablas se quieren obtener los valores.
    - Qué condiciones deben cumplir los registros para que sus valores sean recuperados.

De esta forma, a partir de una estructura de nodo se puede generar una sentencia SQL que se ejecute contra la base de datos y recupere un conjunto de registros el cual podremos manipular a través de metodos/conceptos.

**Cual es la funcion de los metodos?**

    Recogen código procesable escrito en lenguaje LN4, C++ o llamadas a métodos de DLL externas. El resultado obtenido al procesar este código no se asigna al elemento. Sin embargo, desde el codigo de un método se pueden asignar valores a otros elementos de tipo campo o concepto.

**Cual es la función de los conceptos?**

    Al igual que los metodos recogen código procesable escrito en lenguaje LN4, C++ o llamadas a métodos de librerías de enlace dinámico (DLL) externas. Cuando se ejecuta el código de un concepto, el valor que se obtiene se asigna al concepto. A diferencia de los metodos, los conceptos pueden grabar su valor en una columna de la base de datos lógica (recordemos que los metodos solo retornan un valor y puede ser asignado a un campo/propiedad/concepto).

**Cual es la funcion de las propiedades** 

    Estos elementos recogen valores que no se leen de la base de datos, aunque estos valores pueden ser asignados dentro de un metodo/concepto. Tampoco llevan asociadas instrucciones de procesamiento. Se utilizan para recoger valores solicitados al usuario en tiempo de ejecución, u obtenidos durante la ejecución de la regla LN4 de un elemento de tipo método o concepto. Aunque estos elementos no lean su valor de ninguna columna de la base de datos, sí podrán escribir el mismo en una columna (en la tabla logica) de dicha base de datos utilizando la propiedad de tipo registro.

**Cual es la funcion de los campos?**

    Los elementos de tipo campo están asociados a columnas de tablas de la base de datos. Mediante los elementos de tipo campo, se puede:
        - Recuperar valores de la base de datos para mostrarlos en pantalla, generar informes o procesarlos en cálculos complejos.
        - Escribir y actualizar los valores de las columnas de la base de datos.
    
    El valor que recoge un elemento de este tipo en un momento dado se corresponde con el valor incluido en la columna de la base de datos asociada a la estructura de nodo.

    Una columna no lleva asociadas instrucciones de procesamiento. Sin embargo, puede procesar los valores de los elementos de tipo campo en las reglas LN4 de elementos de tipo método o concepto. El lenguaje LN4 permite leer, escribir y actualizar el valor de los elementos de tipo campo y trabajar con ellos como si fueran variables.

## Ámbito de los elementos

    Los elementos se pueden clasificar según su ámbito. Este ámbito indica si su valor o su codigo se aplica a:




