# Clase #1 - Entrada y salida de datos

En esta clase veremos las entradas y salidas de datos.

Antes de empezar veremos primeros que son los comentarios.

## Comentarios
Los comentarios son lineas de código que no son tomadas en cuentas por el compilador y sirven para documentar o explicar un fragmento de un código.

```java
//Esto es una linea de comentario

/*
  Esto es un comentario en bloque 
  tambien se le conoce como multi-línea
*/
```

## Tipos de datos
Un tipo de dato informático o simplemente tipo es un atributo de los datos que indica al ordenador (y/o al programador) sobre la clase de datos que se va a trabajar. Esto incluye imponer restricciones en los datos, como qué valores pueden tomar y qué operaciones se pueden realizar.

| Tipos de datos | Explicacion | Ejemplo |
| ------ | ------ | ------ |
| string | Permite ingresar letras o caracteres | "Clase de Java |
| char   | Permite ingresar letras o caracteres | "Hola" |
| float  | Numeros con decimales con un maximo de 8 decimales | 2.33 |
| double | Numeros con decimales con un maximo de 16 decimales| 3.33 |
| boolean | verdadero y falso | true/false |

Ahora veremos como declarar una variable y asignarle un valor

```java
String variable = "Hola a todos !!";
```

## Salida de datos
Mostrar texto por consola utilizaremos `System.out.print("")` y dentro de las comillas dobles ira el texto a mostrar por consola.
 
```java
System.out.print("Esto se visualizara en la pantalla");
```

En caso de querer imprimir una variable solo tenemos que colocarla como si estuvieramos colocando texto

```Java
String saludo = "Hola a los nuevos programadores";
System.out.print(saludo); 
```

## Entrada de datos
La entrada de datos o lectura de datos es muy simple. Para leer los datos por teclado se hace usara el objeto `Scanner` junto a la funcion correspondiente a la variable, ejemplo: 


| Tipos de datos | Funcion       |
| -------------- | ------------- |
| string         | next()        | 
| char           | next()        |
| float          | nextFloat()   |
| double         | nextDouble()  |
| int            | nextInt()     |
| boolean        | nextBoolean() |

👀 PD: ojo con el tipo de dato y lo que introduces.

```java
  Scanner sc = new Scanner(System.in);	

  System.out.print("Introducir nombre: ");
  String nombre x = sc.next();

  System.out.print("Mi nombre es: " + nombre);
```

