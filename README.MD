# Versión del curso
Versión actual: v1.2.2

# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Subbrayado
Underline 1
-----------

Underline 2
===========

# Fornato de enfasis
- letra *italica* de la primera forma.
- letra _italica_ de la segunda forma.
- formato **bold o strong**.
- formato __bold o strong__ de la 2º forma.
- formato ~~tachado~~.
- Aqui podemos usar *formato italico*, pero también **bold** y ~~tachado~~

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.

- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
 
 # Links
 - <a href="http://google.com">Esto es un link HTML></a>
 - [Esto es un link en MarkDown](http://www.google.com)
  - [Esto es un link al index](index.html)

  #Imagenes

 ![logo github](https://image.flaticon.com/icons/svg/25/25231.svg) 

 # code Snippets
 Código en JSON
 ```Codigo en JSON
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

Codigo javascript
```javascript
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
| Nombre | Apellido | Documento |
|--------|----------|-----------|
| Maxi   | Burgos   | 354581    |
| Tomas  | Tompson  | 457554    |


# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:
> Esto es otra cita.

# Lineas divisoras u horizontales

Esto es un texto que será dividido y siempre separado por un espacio

---
Dividido por ***

***

Dividido por guiones bajos

___

# Saltos de linea con un enter 
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.<br>
Esto es nuestro cuarto parrafo.


