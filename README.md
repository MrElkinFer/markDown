# Primera guia de Markdown

Este repositorio tiene la finalidad de funcionar como guía personal para entender la funcionalidad de Markdown, leguaje ligero usado para la documentación de proyectos en HTML y XML.

---

## para títulos tenemos:

Para tenerun nivel de títulos tenenmos que anteceder el texto del título con un '#' seguido de un espacio. El nivel del título dependerá de el número de númerales (#) que se agrege hasta el título 6 (###### ), algo como lo que se muestra a continuación:

---

# Título 1

## Título 2

### Título 3

#### Título 4

##### Título 5

###### Título 6

---

Las respectivas representación en Markdown sería:

```
# Título 1

## Título 2

### Título 3

#### Título 4

##### Título 5

###### Título 6
```

---

## Formato de Texto:

la sintaxis escrita para conseguir las fuentes _Italica_, **Strong** y ~~subrayada~~ es la siguiente:

_This is an italic text_

**This is an strong text**

~~This is an underlined text~~

---

Su respectiva sintaxis en Markdown es:

    _This is an italic text_

    **This is an strong text**

    ~~This is an underlined text~~

## En cuanto a listas

### Listas no ordenadas:

Para generar una lista de este tipo tan solo se debe agregar el signo menos o guión, también con asterisco ( - , \* ), junto con un espacio. Para lograr sub-listas tan solo se debe agregar un **TAB** antes de el simbolo.

la sintaxis escrita es la siguiente:

- Primer bullet

  - Primer sub bullet

  - Segundo sub bullet

  - Tercer sub bullet

    - Más de lo mismo... :smile:

- Segundo bullet

- Tercer bullet

- n-ésimo bullet

Así es como se representaría en Markdown:

    - Primer bullet

    - Primer sub bullet

    - Segundo sub bullet

    - Tercer sub bullet

      - Más de lo mismo... :smile:

    - Segundo bullet

    - Tercer bullet

    - n-ésimo bullet

### Listas numeradas:

La generación de este tipo de listas es similar al de las listas no ordenadas, con la diferencia que no se usa el signo menos o el asterisco ( - , \* ), en cambio usamos la numeración que deseamos. De momento no se puede o permite una sub numeración ( _Ej: 1.1.2.3_ ). LA visualización de estas listas es como se muestra a continuación:

1. Primer bullet

   - Primer sub bullet

   - Segundo sub bullet

   - Tercer sub bullet

     1. Más de lo mismo... :smile:

2. Segundo bullet

3. Tercer bullet

4. n-ésimo bullet

---

La visualización del código usado para la creación del ejemplo anterio es la siguiente:

    1. Primer bullet

      - Primer sub bullet

      - Segundo sub bullet

      - Tercer sub bullet

        1. Más de lo mismo... :smile:

    2. Segundo bullet

    3. Tercer bullet

    4. n-ésimo bullet

> **Nota:** en este momento no se puenden tener listas literales ( _**Ej:** a. b. etc_ )

---

### Acerca de los enlaces (links) o hipervinculos:

la sitaxis de los enlaces consiste en una pareja de llaves que encierran la palabra o nombre que cargará con el enlace así: [YouTube], por otra parte entre paréntesis a continuación del nombre se pondrá la **URL** del sitio al cual de debe direccionar y como opción un label que se mostrará cuando deslicemos el curso arriba del nombre del enlace:

**La sintaxis en Markdown quedaría así:**

>     [YouTube](http://www.youtube.com "Home Youtube")

**El resultado que se presenta para el enlace es este:**
[YouTube](http://www.youtube.com "Home Youtube")

---

## Referencias a lineas de código

Para generar una referencia a un código particular podemos generar un espacio con tres acentos invertidos y cerrando el mismo espacio de la misma manera tal y como se ilustra a continuación:

    ```JavaScript
      // Se puede usar para un bloque de código
      console.log("Hola Mundo!!!");
      return null;
    ```

la visualización de Markdown es la siguiente:

```JavaScript
  // Se puede usar para un bloque de código
  console.log("Hola Mundo!!!");
  return null;
```

Como es de notar, se puede eleguir el lenguaje en el que el bloque de código esta escrito, en este caso JavaScript.

Para una sola linea basta con usar un solo par de ascentos invertidos, pero en este caso no puedes definir el lenguaje, es algo así:

    `print("Hola mundo!!!");`

el resultado de la anterior sintaxis es:

`print("Hola mundo!!!");`

---

## Tablas

Para hacer uso de las tablas se requiere de los simbolos **|** ( _barra vertical_) y **-** (guión o signo menos), la sintaxis de una tabla así como su visualización se muestran a continuación:

**Sintaxis:**

    |   CIUDAD | CANTIDAD |     PRECIO |
    | -------: | -------: | ---------: |
    |   Bogotá |   20.000 |       $500 |
    | Medellín |   10.000 |     $2.000 |
    |     Cali |    9.000 |     $3.000 |
    |    Total |          | **$5.500** |

**Resultado:**

|   CIUDAD | CANTIDAD |     PRECIO |
| -------: | -------: | ---------: |
|   Bogotá |   20.000 |       $500 |
| Medellín |   10.000 |     $2.000 |
|     Cali |    9.000 |     $3.000 |
|    Total |          | **$5.500** |

---

## Carga de imágenes

La carga de imagenes dentro de Markdown se puede ver como un caso especial de la generación de enlaces, auncuando se puede llamar enlaces locales, su sintaxis en la siguiente:

    ![Flores](https://photos.app.goo.gl/3Y2Bt1....)

**Así se vería el resultado en Markdown:**

![Flores](Flores.jpg)

---

## Lineas de separación

Para separar secciones a veces necesitamos Lineas como las que se pueden ver entre la imagen y el título de esta sección o arriba de este texto. La sitaxis de estas lineas consiste en el uso de tres guines bajos **\_** consecutivos, no más:

**Sintaxis:**

    ___

**Resultado:**

---

---

Versiones:
**Primera versión: 15/05/2024.**
