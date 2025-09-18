# Operadores y expresiones

## Operadores y expresiones

### ¿Qué es una expresión? 

Una expresión en programación es una combinación de valores, variables y operadores que da como resultado un nuevo valor.

Por ejemplo:

```
edad ← 16
edad + 1          // Es una expresión que da como resultado 17
```

En ese caso, la expresión edad + 1 tiene como resultado 17, pero no cambia el valor de la variable edad si no se asigna ese resultado a otra variable o a la misma.

***

### ¿Qué son los operadores?

Los operadores son los símbolos que usamos para construir expresiones. Sirven para hacer operaciones matemáticas, comparaciones y acciones lógicas.

***

### Tipos de operadores

#### 1. Operadores aritméticos

Se usan para realizar operaciones matemáticas.

| Operador | Significado     | Ejemplo | Resultado |
| -------- | --------------- | ------- | --------- |
| +        | Suma            | 3 + 2   | 5         |
| -        | Resta           | 7 - 4   | 3         |
| \*       | Multiplicación  | 6 \* 2  | 12        |
| /        | División real   | 8 / 3   | 2.67      |
| div      | División entera | 8 div 3 | 2         |
| mod      | Módulo (resto)  | 8 mod 3 | 2         |
| ^        | Potencia        | 2 ^ 3   | 8         |

Importante: En PSeInt usamos div y mod en lugar de los símbolos / y % que se usan en otros lenguajes como Java o Python.

***

#### 2. Operadores relacionales

Se usan para comparar valores y devuelven un resultado booleano: Verdadero o Falso.

| Operador | Significado       | Ejemplo | Resultado |
| -------- | ----------------- | ------- | --------- |
| =        | Igual a           | 5 = 5   | Verdadero |
| ≠ o <>   | Distinto de       | 5 ≠ 3   | Verdadero |
| <        | Menor que         | 3 < 8   | Verdadero |
| >        | Mayor que         | 10 > 7  | Verdadero |
| <=       | Menor o igual que | 4 <= 4  | Verdadero |
| >=       | Mayor o igual que | 6 >= 9  | Falso     |

***

#### 3. Operadores lógicos

Se usan para combinar condiciones y tomar decisiones más complejas.

| Operador | Significado | Ejemplo                       | Resultado                            |
| -------- | ----------- | ----------------------------- | ------------------------------------ |
| Y        | AND (y)     | edad > 18 Y ciudad = "Madrid" | Verdadero si ambas lo son            |
| O        | OR (o)      | nota > 5 O asistencia > 75    | Verdadero si al menos una lo es      |
| NO       | NOT (no)    | NO (esMayor)                  | Invierte el valor: Verdadero ↔ Falso |

**Álgebra de Boole**

<figure><img src="../.gitbook/assets/Tabla de verdad AND (&#x26;&#x26;).png" alt="" width="288"><figcaption></figcaption></figure>



<figure><img src="../.gitbook/assets/Tabla de verdad NOT (!).png" alt="" width="282"><figcaption></figcaption></figure>

### Precedencia de operadores

Cuando hay varias operaciones en una expresión, no todas se ejecutan en el orden en que aparecen. Hay unas que se resuelven antes que otras:

Orden de precedencia (de mayor a menor prioridad):

1. Paréntesis ()
2. Potencias ^
3. Multiplicación y división \*, /, div, mod
4. Suma y resta +, -
5. Comparaciones <, >, =, etc.
6. Lógicos: NO, Y, O

#### Ejemplo:

```
resultado ← (3 + 2) * 4      // Primero suma, luego multiplica → resultado = 20
```

Si no usáramos paréntesis:

```
resultado ← 3 + 2 * 4        // Primero multiplica → 3 + 8 = 11
```

***

### Expresiones de asignación

Cuando el resultado de una expresión se guarda en una variable, estamos haciendo una asignación.

```
suma ← a + b
media ← (nota1 + nota2) / 2
```

***

### Importancia de los operadores

Aprender a usar bien los operadores es fundamental para:

* Calcular valores correctamente
* Evaluar condiciones (por ejemplo: ¿puede entrar? ¿está aprobado?)
* Combinar decisiones lógicas (por ejemplo: si es mayor de edad y tiene carnet)
* Escribir código claro y sin errores

***

### Actividad práctica recomendada

Traduce las siguientes expresiones cotidianas a código:

* “Si la edad es mayor o igual a 18, puede votar”
* “El precio total es el precio base más el IVA”
* “¿El número es divisible entre 5?”

