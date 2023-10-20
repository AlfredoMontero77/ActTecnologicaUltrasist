# Aprendiendo _Markdown_

## Parrafo

Esto es un parrafo

Es un hecho establecido hace demasiado tiempo que un lector se distraerá con el contenido del texto de un sitio mientras que mira su diseño. El punto de usar Lorem Ipsum es que tiene una distribución más o menos normal de las letras, al contrario de usar textos como por ejemplo "Contenido aquí, contenido aquí". Estos textos hacen parecerlo un español que se puede leer. Muchos paquetes de autoedición y editores de páginas web usan el Lorem Ipsum como su texto por defecto, y al hacer una búsqueda de "Lorem Ipsum" va a dar por resultado muchos sitios web que usan este texto si se encuentran en estado de desarrollo. Muchas versiones han evolucionado a través de los años, algunas veces por accidente, otras veces a propósito (por ejemplo insertándole humor y cosas por el estilo).

## Estilos

Para cursiva se utiliza guiones bajos: \_ _Esta es una cursiva_ \_

Para negrita se utiliza doble asterisco: \*\***Esta es negrita**\*\*
Mezclado: \*\*\_**_Esta es negrita y cursiva_**\_\*\*\

## Encabezados

Para Encabezado se tiene como html algunos tipos o niveles de encabezados, se utiliza el simbolo **#**(gato, grilla) de acuerdo al nivel de encabezado que se desee se utiliza el simbolo de 1 a 6:  

# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6

## Enlaces

Enlaces: Si desea utilizar enlaces se utiliza corchetes **[]** y parentesis **()** en el primero va el texto a mostrar, en el segundo el vinculo o dirección a utilizar:

**(_Enlace Externo_)**
Enlace a una web
[Yahoo](www.yahoo.com)

**(_Enlace Interno_)**
Enlace a una parte del documento
[Aprendiendo _Markdown_](#aprendiendo-markdown)

## Imagenes

Para presentar Imagen o imagenes en el documento se utiliza el simbolo de admiracion de cierre, corchetes y parentesis **!** **[]** **()**.

descripcion: **!** **[**_nombre de imagen_**]** **(**_url o direccion de ubicacion de la imagen ya se desde el internet o local de nuestro equipo_**)**

![Imagen Ejemplo](/imagen.jpg)

---

Esta es una linea divisora de contenido para dibuar se utiliza **tres guiones medios**_(---)_.

---

## Listas

Para la listas ordenadas se antepone el **1.** _espacio_ texto a listar en esta forma nos enumera el listado.
Tambien se puede utilizar asterisco **(*)** o guion medio **(-)**.

**Lista Enumerada**

\1. Texto
1. Primero
1. Segundo
1. Tercero

**Lista con (*)**

\* Texto
* Primero
* Segundo
* Tercero

**Lista con (-)**

\- Texto
- Primero
- Segundo
- Tercero

### Sublistas

Para crear sublistas se puede mezclar los diferentes tipos de listas, con su respectiva identacion.

1. Primero (1.)
    * Primero punto uno (1.1)
        - Primero punto uno punto uno (1.1.1)
1. Segundo (2.)
    * Segundo punto uno (2.1)
        - Segundo punto uno punto uno (2.1.1)
1. Tercero (3.)
    * Tercero punto uno (3.1)
        - Tercero punto uno punto uno (3.1.1)
    * Tercero punto dos (3.2)
        - Tercero punto dos punto uno (3.2.1)

1. Cuarto (4.)
1. Quinto (5.)

## Citar

Para citar se utiliza el simbolo de **mayor que** **(>)** antes de empezar el citado.

**_Cita una linea_**

\> (Cita)

> Siempre tienes opcion de no tener opinion. - Marco Aurelio.

**_Cita en bloque_**

\> (Bloque)

\> (Bloque)

\> (Bloque)

>Todo lo que escuchamos es una opinion, no un hecho.
>
>Todo lo que vemos es una perspectiva, no la verdad.
>
>Marco Aurelio

## Tablas
Para crear tablas se utiliza el simbolo **|** entre cada parte de la tabla como para formar el encabezado y cuerpo de la tabla se puede combinar con el guion medio **(-)** como para crear la separacion entre el encabezado y el cuerpo de la tabla.

| Nombre | Edad | Correo |
| ------ | ---- | ------ |
| Kelly  | 23   | kellyocampo@gmail.com |
| Anie   | 21   | anieocmapo@gmail.com  |
| Steve  | 20   | steveocampo@gmail.com |
| Luis   | 15   | luisocampo@gmail.com  |

## Escribir codigo

Para escribir lineas de codigo de algun lenguaje, o destacar en algun parrafo alguna palabra reservada de un lenguaje se utiliza el simbolo de tilde grabe **(`)** o tilde inversa con una tilde al inicio y al final de la palabra es _codigo en linea_, para codigo en bloque se utiliza tres tildes **(```)** al inicio y tres tildes al final y se deseamos junto a las tildes de inicio se puede escribir el acronimo del lenguaje de programacion que se hace referencia.

_Ejemplo de codigo en linea_.

La palabra reservada para declarar una variable en JavaScript es `var` y `let`

_Ejemplo de codigo en bloque_.

```php
function restar (a, b){
    return a - b;
}
```
Tambien puedes escribir HTML, markdown te lo soporta y formatea de acuerdo a los tag que utilices.

## Comentarios
En markdown tambien se puede utilizar comentarios y estos utilizan el mismo formato de HTML **(\<!\--)** al inicio **(\-->)** al final.

<\!-- Este es un comentario \-->

