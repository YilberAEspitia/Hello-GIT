# Cabecera H1
Version 1.2.2
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

Soy un underline 1
--
Soy un underline 2
==

# Formatos enfasis
- Formato *italica* de la primer forma
- Formato _italica_ de la segunda forma
- Formato **bold o strong** de la primer forma
- Formato __bold o strong__ de la segunda forma
- Formato ~~tachado~~, formato normal
- Aquí podemos usar *formato italico*, pero **tambien bold**

# Listas
1. Esto es un item de lista ordenada
2. Esto es un item de lista ordenada
3. Esto es un item de lista ordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
- <a href="http://google.com">Google</a>
- [Google markdown](http://google.com)
- [Index](index.html)
- [Markdown](#listas)

# imagenes
<!--![Logo GIT](https://cdn-icons-png.flaticon.com/512/25/25231.png)-->
<img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" width="100" height="100">

# Code snippets
Ruby
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
puts markdown.to_html
```
Javascript
```javascript
var txt1 = "What a very ";
var txt2 = "nice day";
document.getElementById("demo").innerHTML = txt1 + txt2;
```

# Tablas
Markdown
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Yilber | Arley | 1035 |
| Espitia | Florido | 1036 |

HTML
<table>
    <thead>
    <tr>
        <th>Nombre</th>
        <th>Apellido</th>
        <th>Documento</th>
    </tr>
    <thead>
    <tbody>
    <tr>
        <td>Yilber</td>
        <td>Arley</td>
        <td>1035</td>
    </tr>
    <tr>
        <td>Espitia</td>
        <td>Florido</td>
        <td>1036</td>
    </tr>
    </tbody>
</table>

# Citas
Esto es un texto referente a una cita que pondremos debajo
> Esto es una cita

Esto es otro texto que no se relaciona con la cita anterior
> Esto es otr cita

# Lineas divisoras
Esto es un texto dividido por guiones medios

---
Esto es otro texto dividido por asteriscos

***

Esto es otro texto dividido por guiones bajos

# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro segundo parrafo.
- Lista

- Lista 2
- Lista 3