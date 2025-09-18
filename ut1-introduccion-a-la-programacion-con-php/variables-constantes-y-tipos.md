# Variables, constantes y tipos

## Variables, constantes y tipos

### ¿Qué es una variable?

En programación, una variable es un espacio de memoria con nombre que utilizamos para guardar información que puede cambiar mientras el programa se ejecuta.

Podemos pensar en una variable como una caja con una etiqueta (el nombre de la variable) y un contenido que podemos leer o modificar.

Por ejemplo, podríamos tener una variable llamada edad que almacene el número 17.

```
edad ← 17
```

Más adelante en el programa, podríamos cambiar ese valor:

```
edad ← 18
```

Así como cambiamos el contenido de una caja, podemos modificar el valor de una variable cuando lo necesitemos.

***

### ¿Qué es una constante?

Una constante es como una variable, pero su valor no cambia durante la ejecución del programa.

Se utiliza cuando queremos guardar un dato que permanece igual todo el tiempo. Por ejemplo:

```
PI ← 3.1416
```

Si tratáramos de cambiar el valor de PI, estaríamos cometiendo un error, porque es una constante.

***

### Diferencias entre variables y constantes

| Característica    | Variable              | Constante               |
| ----------------- | --------------------- | ----------------------- |
| ¿Cambia su valor? | Sí, puede cambiar     | No, permanece igual     |
| ¿Cuándo se usa?   | Cuando el valor varía | Cuando el valor es fijo |
| ¿Ejemplo?         | nota ← 8.5            | IVA ← 0.21              |

***

### ¿Cómo se nombran las variables?

Existen algunas reglas y buenas prácticas para nombrar variables:

* El nombre debe empezar por una letra.
* No debe contener espacios (usa guiones bajos o mezcla de mayúsculas y minúsculas si es necesario).
* Debe ser descriptivo: que indique lo que almacena.

Ejemplos correctos:

```
nombre
edad
precioProducto
total_factura
```

Ejemplos incorrectos:

```
1edad       ← No puede empezar con número
mi edad     ← No puede tener espacios
@precio     ← No se permiten símbolos especiales
```

***

### ¿Qué son los tipos de datos?

Los tipos de datos indican qué tipo de valor puede almacenar una variable o constante. Esto permite al programa saber cómo debe trabajar con ese dato.

Los más comunes son:

* Enteros (int): números sin decimales (por ejemplo: 3, -15, 202)
* Reales o decimales (float): números con decimales (por ejemplo: 3.14, -2.5, 100.0)
* Cadenas de texto (string): secuencias de caracteres (por ejemplo: “Hola”, “Antonio”, “abc123”)
* Booleanos (bool): verdadero o falso (Verdadero o Falso)
* Carácter (char): un único carácter (por ejemplo: ‘A’, ‘1’, ‘\*’)

***

### Ejemplos de variables con tipo de dato

```
nombre ← "Lucía"              // Cadena de texto
edad ← 16                     // Entero
altura ← 1.65                 // Real
esMayorDeEdad ← Falso         // Booleano
inicial ← 'L'                 // Carácter
```

En algunos lenguajes como Java es obligatorio indicar el tipo de dato al declarar la variable. En pseudocódigo, esto se suele deducir del valor asignado.

***

### ¿Por qué son importantes los tipos de datos?

* Permiten controlar cómo se usan las variables: no se puede sumar un texto con un número.
* Ayudan a detectar errores antes de que se ejecute el programa.
* Optimiza la forma en que el ordenador gestiona la información.

***

### Operaciones con variables

Con las variables podemos realizar operaciones matemáticas, comparaciones, asignaciones, etc. Lo veremos en más detalle en el siguiente apartado, “Operadores y expresiones”.

***

### Recomendación

A medida que vayas creando programas, intenta usar variables con nombres significativos, el tipo de dato correcto y buena organización.

Por ejemplo:

```
nombre ← "Sara"
salario ← 1200.50
numero_hijos ← 2
```

Este código es mucho más claro que:

```
x ← "Sara"
y ← 1200.50
z ← 2
```

