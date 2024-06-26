Primera guía de Markdown

Este repositorio tiene la finalidad de funcionar como guía personal para entender la funcionalidad de Markdown, leguaje ligero usado para la documentación de proyectos en HTML y XML.

---

## para títulos tenemos:

Para tener un nivel de títulos tenemos que anteceder el texto del título con un '#' seguido de un espacio. El nivel del título dependerá del número de numerales (#) que se agrega hasta el título 6 (###### ), algo como lo que se muestra a continuación:

---

# Título 1

## Título 2

### Título 3

#### Título 4

##### Título 5

###### Título 6

---

Las respectivas representaciones en Markdown sería:

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

Para generar una lista de este tipo tan solo se debe agregar el signo menos o guion, también con asterisco ( - , \* ), junto con un espacio. Para lograr sablistas tan solo se debe agregar un **TAB** antes del símbolo.

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

> **Nota:** en este momento no se pueden tener listas literales ( _**Ej:** a. b. etc._ )

---

### Acerca de los enlaces (links) o hipervínculos:

la sintaxis de los enlaces consiste en una pareja de llaves que encierran la palabra o nombre que cargará con el enlace así: [YouTube], por otra parte, entre paréntesis a continuación del nombre se pondrá la **URL** del sitio al cual se debe direccionar y como opción un label que se mostrará cuando deslicemos el curso arriba del nombre del enlace:

**La sintaxis en Markdown quedaría así:**

>     [YouTube](http://www.youtube.com "Home YouTube")

**El resultado que se presenta para el enlace es este:**
[YouTube](http://www.youtube.com "Home YouTube")

---

## Referencias a líneas de código

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

Como es de notar, se puede elegir el lenguaje en el que el bloque de código esta escrito, en este caso JavaScript.

Para una sola línea basta con usar un solo par de acentos invertidos, pero en este caso no puedes definir el lenguaje, es algo así:

    `print("Hola mundo!!!");`

el resultado de la anterior sintaxis es:

`print("Hola mundo!!!");`

---

## Tablas

Para hacer uso de las tablas se requiere de los símbolos **|** ( _barra vertical_) y **-** (guion o signo menos), la sintaxis de una tabla así como su visualización se muestran a continuación:

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

La carga de imágenes dentro de Markdown se puede ver como un caso especial de la generación de enlaces, aun cuando se puede llamar enlaces locales, su sintaxis en la siguiente:

    ![Flores](https://photos.app.goo.gl/3Y2Bt1....)

**Así se vería el resultado en Markdown:**

![Flores](Flores.jpg)

---

## Lineas de separación

Para separar secciones a veces necesitamos Líneas como las que se pueden ver entre la imagen y el título de esta sección o arriba de este texto. La sintaxis de estas líneas consiste en el uso de tres guiones bajos **\_** consecutivos, no más:

**Sintaxis:**

    ___

**Resultado:**

---

---

## Comandos únicos en GitHub

Dentro de GitHub podemos usar dos cosas específicas:

1. Listas tipo checklist
2. Emojis :rocket:

---

### Listas tipo CheckList

Para generar una lista de cosas por hacer la sintaxis en la siguiente:

    [ ] Tarea 1 (ToDo)

    [X] Tarea 2 (Check)

    [ ] Tarea 3 (ToDo)

    [X] Tarea 4 (Check)

**La visualización de la lista es la siguiente:**

[ ] Tarea 1 (ToDo)

[X] Tarea 2 (Check)

[ ] Tarea 3 (ToDo)

[X] Tarea 4 (Check)

---

### Emojis

En el caso de los emoji la sintaxis es la siguiente:

    :smile:

[:rocket::smile: :heart_eyes: :grin:Aqui:fire::sunny:](https://gist.github.com/rxaviers/7360908#file-gistfile1-md " emojis list: rxaviers") puedes picar para ver la lista de emojis disponibles para Markdown.

---

Versiones:
**Primera versión: 15/05/2024.**
