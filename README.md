# Cabeceras
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



# Formatos de énfasis
- Formato *itálica* 1
- Formato _itálica_ 2
- Formato ***bold o strong** 1
- Formato __bold o strong__ 2
- Formato ~~tachado~~
- Formato normal
- Formato ~~tachado~~



# Listas
1. Esto es un item de lista ordenada
1. Esto es un item de lista ordenada
1. Esto es un item de lista ordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada



# Links
- [Esto es un link en Markdown](https://google.com)
- [Esto es un link en Markdown](index.html) lleva a la url en GitHub



# Imágenes
- ![Logo GitHub](https://universalarticles.com/wp-content/uploads/2019/11/github-702x459.png)



# Code Snippets: estilos según lenguaje
Se puden consultar los modelos [aquí](https://highlightjs.org/static/demo/).
```JSON
POST /task?id=1 HTTP/1.1
Host: example.org
Content-Type: application/json; charset=utf-8
Content-Length: 137

{
  "status": "ok",
  "extended": true,
  "results": [
    {"value": 0, "type": "int64"},
    {"value": 1.0e+3, "type": "decimal"}
  ]
}
```

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
| Encabezado 1 | Enc2 | Enc3 |
| ------------ | ---- | ---- |
| Valor 1 | Valor 2 | Valor 3 |
| Valor 1 | Valor 2 | Valor 3 |



# Citas
> Esto es una cita
Y sigue aquí

Esto no es una cita

> Esto es otra cita



# Líneas divisoras
Esto es un texto que será dividido por guiones medios

---
Esto es otro texto dividido por asteriscos

***
Esto es otro texto dividido por guiones bajos
___



# Saltos de línea
Esto es nuestro primer párrafo

Esto es nuestro segundo párrafo, creado por el salto de línea al medio

Esto es nuestro tercer párrafo
- Y este cuarto se separa por una lista

