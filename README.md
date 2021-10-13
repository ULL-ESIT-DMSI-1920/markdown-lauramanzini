
# Aprender Markdown
Curso de Desarrollo y Mantenimiento de Sistemas de Informaciones

**Laura Manzini**

# Cabeceras 
Las cabeceras son conocidas también como 'headers' y nos ayudan a desarrollar el texto y organizarlo.

Se pueden haber más formados de cabeceras, que se utilizan ponendo el simbolo `#` seguido por un espacio y el texto. Basado en cuantos `#` se ponen hay diferentes estilos de cabeceras.

`# Header1`  
# Header1


`## Header2`
## Header2


`### Header3`
### Header3


# Formato de texto
Algunas de las funcionalidades que se aprenden en el markdown son los diferentes formatos del texto.

## Texto en italico
El texto en italico se puede escribir en dos manera diferentes:

* A traves del utilizo de un guión bajo que se pone antes y despues del texto que se quieren  poner en italico

    ` _texto en italico_` es _texto en italico_

* A traves del utilizo de un asterisco que se pone antes y despues del texto se quieren  poner en italico

    ` *texto en italico* ` es *texto en italico*

## Texto en negrita
El texto en negrita se puede escribir en dos manera diferentes:

* A traves del utilizo de dos guiónes bajos que se ponen antes y después del texto que se quieren poner en negrita
    
    ` __texto en negrita__` es __texto en negrita__

* A traves del utilizo de dos asteriscos que se ponen antes y después del texto que se quieren poner en negrita
` **texto en italico** ` es **texto en italico** 

## Texto en tachado
El texto en atachado se escribe utilizando las dos tachadas antes y después del texto que se quieren poner en tachado.

`  ~~texto en tachado~~ ` es   ~~texto en tachado~~

## Combinación de los formatos
Se pueden tambíen combinar los diferentes formeatos de que acabamos de hablar.

1. Para escribir el texto al mismo tiempo en negrita y en italico se puede utilizar una de las siguentes maneras:
    -  `***texto en negrita y italico*** ` es decir ***texto en negrita y italico***
    - `**_texto en negrita y italico_** ` es decir **_texto en negrita y italico_** 
    - `*__texto en negrita y italico__* ` es decir *__texto en negrita y italico__* 

2. Se pueden tambíen hacer otra combinaciones de formato de texto como la siguientes:
    - `*_texto_ en negrita y italico* ` es decir **_texto_ en negrita y italico**

    - `_**texto** en negrita y italico_ ` es decir _**texto** en negrita y italico_ 

    - `_~~texto~~ en negrita y italico_ ` es decir _~~texto~~ en negrita y italico_ 
 
 Del mismo modo se pueden hacer muchas más combinaciones.

# Quotes
## Quotar el texto
Cuando se quieren hacer citas **de texto** se pone el símbolo `>` antes de lo que va a ser una cita.

`> esta es una cita`
 > esta es una cita


## Quotar codigo

-  Cuando se quota **una linea de codigo** se pone el símbolo ` antes y después del codigo.

    `int i`


 *Atención*: esta regla es solo valida por el codigo que solo se pone en un unica riga

- Cuando el se quota **más lineas de codigo** se ponen tres ``` antes de empezar a escribir el codigo y al final del mismo codigo

```
int i 
i = 1
i += 12
```
  
# Links
Para generar un link es necesario utilizar el siguente formato: `[link](URL)`.

 Es **importante** que no hay espacios entre los corchetes y los paréntesis redondo.

Por ejemplo el siguente codigo:
```
[link](https://i1.wp.com/mochileroviajando.com/wp-content/uploads/2017/07/lavanda-francia4.jpg?resize=902%2C569&ssl=1) 
```
nos transfiere al siguente [link](https://i1.wp.com/mochileroviajando.com/wp-content/uploads/2017/07/lavanda-francia4.jpg?resize=902%2C569&ssl=1) 

Es tambíen posible poner un enlace que se riefere a un otro file que es puesto sobre el repositorio.

El siguente codigo:
```
[imagen](./pexels-lisa-fotios-1412146.jpg)
```

nos transfiere a la [imagen](./pexels-lisa-fotios-1412146.jpg) que es guardada en nuestro repositorio.

# Imagenes
Para poner una imagen se utiliza el siguente formato: `![link](URL)`.
El utilizo del punto de escalada al principio  permite de añadir fotos en realación a un enlace.

```
![foto](https://i1.wp.com/mochileroviajando.com/wp-content/uploads/2017/07/lavanda-francia4.jpg?resize=902%2C569&ssl=1)
```
![foto](https://i1.wp.com/mochileroviajando.com/wp-content/uploads/2017/07/lavanda-francia4.jpg?resize=902%2C569&ssl=1)

## Imágenes por referencia
Para hacer una referencia a una imagen en el mismo repositorio se pone entre los corchetes redondos la routa para acceder a la imagen.

```
![campo de flores](./pexels-lisa-fotios-1412146.jpg)
```
![campo de flores](./pexels-lisa-fotios-1412146.jpg)


# Listas
Para crear una lista se utiliza el simbolo `*` o el simbolo `-` antes de cada línea.
* esta  
* es
* una
* lista

## Lista ordenada
Para crear una lista ordenada se utilizan numeros seguidos da un punto antes de cada línea.
1. esta
2. es
3. una
4. lista

## Lista anidada
Para crear una lista anidada a un primero elemento de una lista se utiliza la linea siguente y se alinea el simbolo `-` del segundo elemento con la primera letra del elemento anterior.

Para anidar más elementos se procede de la misma manera.

- Primer elemento
  - Segundo elemento
    - Tercero elemento

Se puede también hacer lo mismo con lista ordenadas

11. Primero elemento
   - Segundo elemento
     - Tercero elemento     


# Task
Para crear una lista se utilizan los corchetes `[ ]` y para marcar tareas completadas se utiliza `[x]`.

- [ ] task 1
- [x] task 2

# Mencionar 
En GitHub se pueden mencionar una persona o también un grupo de personas utilizando el simbolo `@`.

El simbolo abre automaticamente una lista de persona o grupo de personas que seleccionar.

La persona recibirá una notificacion sobre la mencíon.

@lauramanzini


# Hacer referencias
Para referenciar issues que se han producido sobre el repositorio es suficiente utilizar el simbolo `#`.

El simbolo abre una lista de issues que se pueden referenciar.

Seleccionando `#1` el GitHub te permite de acceder a el issue 1 `[#1](https://github.com/ULL-ESIT-DMSI-1920/markdown-lauramanzini/issues/1)`









[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=5793195&assignment_repo_type=AssignmentRepo)