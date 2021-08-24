# ¿Cuándo Utilizar Markdown? - Casos de uso
1. Documentación de Proyectos.
2. Apuntes o anotaciones sobre cursos o trabajos escolares.
3. Escribir blogs.
4. Entre otros.

Hay que pensar en que **Markdown** es para escribir, no para hacer código.

**Markdown** es un lenguaje de marcado, lo mismo que HTML.


*Nota: Dentro de mis marcadores, en la sección de "Utilidades Web" hay una sección que contiene artículos relacionados a este lenguaje y a los diferentes editores que pueden utilizarse.*


***


### Párrafos, Saltos de Línea y Encabezados

Para realizar un salto de línea y empezar una frase en una línea siguiente dentro del mismo párrafo, tendrás que pulsar dos veces la barra espaciadora (de manera que sean dos espacios en blanco al final) antes de pulsar una vez intro.  
Esta es una nueva línea dentro del mismo párrafo.


Para hacer un nuevo párrafo hay que dar 2 saltos de línea, o sea, 2 "enter".


En cuanto a los encabezados, existen 6 estilos diferentes:


## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6


***


### Listas Ordenadas y Desordenadas
Para crear listas desordenadas se utilizan asteriscos "*" o guiones intermedios "-"

* Item 1
	* Sub item 1
	* Sub item 2
- Item 2
	- Sub item 1
	- Sub item 2


Para crear listas ordenadas se utilizan números, seguido por un punto "."

1. Item 1
	1. Sub item 1
	2. Sub item 1
2. Item 2
    1. Sub item 1
    2. Sub item 2


***


### Insertar Imagenes y Enlaces
Para poder insertar imagenes se utiliza la siguiente sintaxis:

Sintaxis: ![texto alt](URL o LINK)


Ejemplo:

![Imagen de perfil](https://scontent.fmex10-1.fna.fbcdn.net/v/t1.0-1/p160x160/28952022_1964043806956962_133691611686109184_n.jpg?_nc_cat=105&_nc_ht=scontent.fmex10-1.fna&oh=8aba6725d31667f88fa58ccdc0528feb&oe=5CAF6872)


Para poder insertar URL (enlaces) se usa la siguiente sintaxis:

* [Texto](URL o LINK)

* [Pizza Planeta](www.pizzaplaneta.tk)


        Nota: El siguiente es un pequeño parrafo mostrando un sencillo "hack". Este hack debe colocarse siempre al final del documento, si la palabra piensa utilizarse multiples veces y se quiere que sea un enlace.

Ejemplo: [Pizza Planeta] abre sus puertas blah blah blah. A partir de ahora [Pizza Planeta] te ofrece blah blah.

[Pizza Planeta]: www.pizzaplaneta.tk

Puede aplicarse el mismo hack al utilizar imagenes.

![Imagen de perfil][Foto]

[Foto]: https://scontent.fmex10-1.fna.fbcdn.net/v/t1.0-1/p160x160/28952022_1964043806956962_133691611686109184_n.jpg?_nc_cat=105&_nc_ht=scontent.fmex10-1.fna&oh=8aba6725d31667f88fa58ccdc0528feb&oe=5CAF6872


***


### Insertar líneas de Código
Hay 2 tipos de código:

1. Código en línea: Es el que se inserta mientras se va redactando un párrafo, y la(s) palabra(s) se envuelve(n) entre 2 comillas sencillas.

    Ejemplo: En JS las variables se declaran con la palabra reservada `let` y las constantes `const`.


2. Código en bloque: La descripción no es necesaria, creo que se entiende. Se envuelve entre 3 comillas sencillas de apertura y 3 de cierre. Incluso, puede indicarse qué lenguaje se utiliza para resaltar sus propias palabras reservadas.
Incluso puede encerrarse codigo usando este simbolo "~"

    ```javascript
    const saludo = () => "Hola"
    ```

    ~~~javascript
    const despedida = () => "Adios"
    ~~~

***


### Texto, Citas

* Negritas: Para remarcar palabras se encierra entre asteriscos "*". Dos al principio y Dos al final.

        Ejemplo: **Negrita**

* Italica o inclinada: Para escribir texto con estilo "Italic" se encierra entre asteriscos "*". Uno al principio y uno al final.

        Ejemplo: *Italica*

* Negrita Italica: Para escribir texto que tenga **Negritas** y también *Italica* se encierra entre asteriscos "*". Tres al principio y Tres al final.

        Ejemplo: ***Negrita Italica***


* Para poder redactar citas de otros textos solo se usa el signo ">":

    > Esto es una cita de algun autor.  
    Seguimiento de cita Textual.


---


### Tablas de datos
Se usan para tabular y mostrar datos ordenados.  
Se utiliza el simbolo "|", que es una barra vertical, y 3 guiones "-" como minimo.  
Se puede alinear el contenido de las tablas colocando dos puntos ":", ya sea al final para alinear a la derecha, al principio para alinear a la izquierda o en ambas posiciones para centrar.


Mes | Concepto | Venta
:---|:---:|---:
Enero | Cursos | 1,000
Febrero | Suscripciones | 2,000


___


### Herramientas Para Utilizar MD
* Editores en línea:  
  * [Stack Edit](https://stackedit.io)
  * [Dillinger](https://dillinger.io)
  * [Typora](https://typora.io)

* Extensiones para Google Chrome
  * [Markdown Here](https://markdown-here.com)
  * [Markdown Preview Plus](https://github.com/volca/markdown-preview)

* Editores Para Programadores
  * [Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown)

* Aplicaciones Para Hacer Anotaciones
  * [Boostnote](https://boostnote.io)
  * [Simple Note](https://simplenote.com)

* Herramientas o Servicios Que Soportan MD
  * Slack
  * Trello
  * GitHub
  * Medium
  * Stackoverflow
  * EDteam