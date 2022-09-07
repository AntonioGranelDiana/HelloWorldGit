# Versión de curso
Versión Actual:v1.2.2

# Cabecera 
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========
# Formato de énfasis
- formato *italica* de la primera forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primera forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- aquí podemos usar *formato italico*, pero también
- **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
- Esto es un item  lista desordenada.                 
- Esto es un item  lista desordenada.                 
- Esto es un item  lista desordenada. 

# Links
- <a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://google.com)
- [Esto es un link en index](index.http)

# Imagenes
![Logo Github](https://cdn.icon-icons.com/icons2/2351/PNG/512/logo_github_icon_143196.png)

# Code Snippets
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Código en Javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```
# Tablas
|Nombre | Apellido | Documento |
| ----- | -------- | --------- |
| Maxi  | Burgos   | 657464    |
| Tomás | Tompson  | 554564    |

# Citas
Esto es un texo referente a una cita que pondremos debajo:
> Esto es una cita.



Esto es otro texto que no se relaciona con la cita anterior.
> Esto es otra cita.

# Lineas Divisiras
Esto será un texto que será dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos.

***
Esto es otro texto dividido por guiones bajos.
___

# Salto de líneas
Esto es nuestro primer párrafo.

Esto es nuestro segundo párrafo.

Esto es nuestro segundo párrafo.

  