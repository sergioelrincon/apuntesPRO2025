# PSeint

## Características del pseudocódigo en PSeInt

Una vez que ya entendemos qué es un pseudocódigo y cómo nos ayuda a expresar la lógica de nuestros algoritmos sin preocuparnos aún por la sintaxis de un lenguaje real como Java, vamos a centrarnos en cómo se escribe el pseudocódigo en PSeInt, el entorno que vamos a utilizar en esta etapa del curso.

PSeInt es una herramienta diseñada especialmente para estudiantes que están comenzando a aprender a programar. Su pseudocódigo no sigue un estándar oficial, sino que utiliza una sintaxis simplificada inspirada en el español.

Aunque no es un lenguaje de programación real, PSeInt permite ejecutar los algoritmos escritos en pseudocódigo, para que podamos probarlos y ver qué resultado dan.

A continuación, te explico las principales características del pseudocódigo que se utiliza en PSeInt.

***

### 1. Es un pseudocódigo estructurado

En PSeInt escribimos nuestros algoritmos de forma ordenada, con una estructura básica que normalmente incluye:

```
Proceso nombre_del_algoritmo
    // Aquí va el contenido del algoritmo
FinProceso
```

Por ejemplo:

```
Proceso saludo
    Escribir "Hola, mundo"
FinProceso
```

***

### 2. Las instrucciones se escriben en español

Una de las principales ventajas de PSeInt es que la mayoría de sus palabras clave están en español, lo que facilita su comprensión.

* Escribir para mostrar mensajes por pantalla.
* Leer para pedir datos al usuario.
* ← para asignar valores a variables.

Por ejemplo:

```
nombre ← "Sergio"
Escribir "Hola", nombre
```

***

### 3. No se definen tipos de datos explícitamente

En pseudocódigo general solemos definir los tipos de datos, como entero, real, cadena, etc.

Sin embargo, en PSeInt no es obligatorio indicar el tipo de dato de una variable. PSeInt intentará deducir automáticamente si es un número, una cadena, etc., según el valor que le asignemos.

Esto quiere decir que podemos hacer lo siguiente sin errores:

```
nombre ← "Lucía"
edad ← 17
```

Y PSeInt se encargará de tratar nombre como cadena de texto y edad como número.

> Nota: Aunque se pueden declarar tipos si se quiere (Definir edad Como Entero), en este primer momento no es necesario, y muchos algoritmos funcionarán sin hacerlo.

***

### 4. No se pueden declarar constantes

A diferencia de otros lenguajes de programación (como Java), en PSeInt no existe una forma oficial de declarar constantes.

Esto significa que si queremos representar un valor que no debe cambiar (por ejemplo, el valor del IVA o del número Pi), simplemente debemos acordarnos de no modificarlo manualmente durante el algoritmo.

Por ejemplo:

```
iva ← 0.21
precioFinal ← precio + precio * iva
```

Aquí iva se comporta como una constante porque nosotros decidimos no cambiarla, pero PSeInt no impide que lo hagamos.

***

### 5. No distingue entre variables numéricas enteras y reales (por defecto)

Como no se definen los tipos explícitamente, una variable puede contener tanto enteros como números con decimales, y PSeInt los manejará internamente.

```
numero ← 5
numero ← numero / 2        // Ahora vale 2.5
```

> Este comportamiento es diferente a lo que encontraremos después en Java, donde sí debemos especificar el tipo (por ejemplo, int o double) y se deben cumplir ciertas reglas al mezclar tipos.

***

### 6. Las cadenas de texto se escriben entre comillas

Para representar texto (también llamado cadena de caracteres) se usan comillas dobles "...":

```
nombre ← "Carlos"
```

Y podemos mostrar mensajes combinando texto y variables:

```
Escribir "Hola", nombre
```

***

### 7. Los comentarios se escriben con&#x20;

### // 

Podemos añadir comentarios al código para explicar lo que hace cada parte. Estos comentarios no se ejecutan.

```
// Este algoritmo calcula el doble de un número
numero ← 5
doble ← numero * 2
Escribir "El doble es", doble
```

Los comentarios son muy útiles para que tú (y otras personas) entiendan qué hace tu algoritmo cuando vuelvas a verlo en el futuro.

***

### 8. No es sensible a mayúsculas y minúsculas

En PSeInt no importa si escribes Escribir, escribir o ESCRIBIR: funciona igual. No obstante, es buena práctica escribir con mayúscula inicial para las instrucciones (Escribir, Leer, etc.) y usar minúsculas para las variables (nombre, edad, etc.), por claridad.

***

### Conclusión

El pseudocódigo de PSeInt es una forma sencilla y cercana de iniciarse en la programación:

* Está en español
* No necesita declarar tipos ni constantes
* Tiene una estructura clara
* Se puede ejecutar para comprobar si funciona



Con él vamos a empezar a traducir nuestra lógica en código, antes de pasar a escribir programas reales con Java.

