# Pasos para crear un repositorio

Índice
- [Pasos para crear un repositorio](#pasos-para-crear-un-repositorio)
- [Caracteres especiales](#caracteres-especiales)
- [Saltos de línea](#saltos-de-línea)
- [Comentarios](#comentarios)
- [Negrita](#negrita)
- [Citas](#citas)
- [Listas](#listas)
- [Enlaces o links](#enlaces-o-links)
- [Tachado](#tachado)
- [Líneas separadoras o regla horizontales](#líneas-separadoras-o-regla-horizontales)
  - [Líneas separadoras escrita sin espacios (se verá igual que la otra)](#líneas-separadoras-escrita-sin-espacios-se-verá-igual-que-la-otra)
  - [Líneas separadoras escrita con espacios (se verá igual que la otra)](#líneas-separadoras-escrita-con-espacios-se-verá-igual-que-la-otra)
- [Imágenes](#imágenes)
  - [Imágenes con enlace](#imágenes-con-enlace)
- [Código en línea](#código-en-línea)
- [Códigos de bloque](#códigos-de-bloque)
- [Task List](#task-list)
- [Task List + iconos](#task-list--iconos)
- [Tablas](#tablas)
- [Mensajes de advertencia](#mensajes-de-advertencia)
- [Comandos](#comandos)

# Caracteres especiales
Para escribir caracteres especiales se usa la barra \ delante de cada caracter.
# Saltos de línea
Dos espacios para salto de línea, enter dejando una linea en blanco para dejar una línea vacía. Con un enter solo se traduce en un whitespace.
# Comentarios
Para hacer comentarios hay que usar el comando \<!--texto--> <!--Esto no se mostrará en el texto--> 


A tener en cuenta: [comment]: <> (Comentario que debe ir solo)  
[//]: <> (Comentario que debe ir solo)  
[//]: # (Comentario que debe ir solo)  
<!--Comentario que puede ir o no solo-->
<!--Comentario
multilínea
que debe ir solo-->

# Negrita
Se pone con \*\*Texto** o con \_\_Texto__, que son dos barras bajas  
\*Texto en cursiva con asteriscos*  
\_Texto en cursiva con barra bajas_  
\*\*\*Texto en negrita y cursiva con asteriscos***  
\_\_\_Textos en negrita y cursiva con barra bajas___  

# Citas
>“¡A mi señal, ira y fuego!🔥”  - Máximo Décimo Meridio.
>>Frase

Se escriben con \> al principio de la cita. Se puede indexar añadiendo los \>

# Listas
- Item 1
- Item 2
* Item 3
* Item 4
+ Item 5
+ Item 6
1. Item 1
2. Item 2
3. Item 3  

o sino
1. Item 1 
1.1. Subitem 1.1  
    1.2. Subitem 1.2
2. Item 2
    * Subitem ded item2
* Item 3
    * Subitem ded item3
      * Subitem del subitem3

Las listas se crean añadiendo los símbolos \- \* \+ o irlas listando con numeros y punto al principio de la fras más whitespace. En el momento que se cambia de símbolo se crea un espacio entre Item e Item. Para acabar una lista dejar una linea vacía.

# Enlaces o links
<http://google.com/>  
\<se pone el texto aquí>  
[Visitar Google](https://www.google.es "Texto (cuando ponemos el cursor encima)")

# Tachado
~~Hola~~  
\~~Texto~~

# Líneas separadoras o regla horizontales
## Líneas separadoras escrita sin espacios (se verá igual que la otra)
Contenido 1  

*** 
Contenido 2 (dejar un espacio entre el último texto y las tres líneas)

---
Contenido 3
___
## Líneas separadoras escrita con espacios (se verá igual que la otra)
Contenido 1
* * *
Contenido 2
- - -
Contenido 3
_ _ _

# Imágenes
![Este contenido se mostrará cuando la imagen no se pueda cargar, como texto alternativo](https://user-images.githubusercontent.com/32896437/153675215-dff3448c-56bc-4da0-9cf1-6a394fd9c6f8.png "Texto a mostrar cuando nos situamos sobre la imagen. En este caso sería Baile de la película Pulp Fiction")
## Imágenes con enlace
[![a](https://www.google.es/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)](www.google.es)  
<!-- Ruta URL de la IMG + Descripción-->
[1]:https://user-images.githubusercontent.com/32896437/153675215-dff3448c-56bc-4da0-9cf1-6a394fd9c6f8.png "Pulp Fiction"
<!-- Enlace -->
[2]: https://es.wikipedia.org/wiki/Pulp_Fiction
<!-- Juntando la descrición con el resto de partes partes -->
[![ALT text][1]][2]
# Código en línea
Etiqueta HTML5: `<!DOCTYPE html>`  
Etiqueta HTML: `<html></html>`  
Etiqueta HEAD: `<head></head>`  
Etiqueta BODY: `<body></body>`  
# Códigos de bloque
``` html
<!DOCTYPE html>
<html lang="en">
<head>
</head>
<body>
</body>
</html>
```

# Task List
- [ ] Elemento no finalizado  
- [x] Elemento finalizado
# Task List + iconos
:white_check_mark: Elemento finalizado  
:x: Elemento finalizado

# Tablas
|Header |Column 1 | Column 2 | Column 3  |
|:--- |:---- |:----:| ----:|
|1. Row| is | is | is  |
|2. Row| left | nicely | right  |
|3. Row| aligned | centered | aligned  |

# Mensajes de advertencia
| :exclamation:  This is very important   |
|-----------------------------------------|
| :zap:        Ignore at your own risk!   |
|-----------------------------------------|
| :warning: WARNING          |
|:---------------------------|
| I should warn you ...      |
| :boom: DANGER              |
|:---------------------------|
| Will explode when clicked! |

# Comandos
![Quizá no carga](https://miro.medium.com/max/1400/1*CghMJVoX3DfXTPSvh3c5hA.jpeg "Comandos Markdown")
