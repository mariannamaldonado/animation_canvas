CHEAT SHEET
============


*Hoja de referencia con atajos*

--

|  | Descripción |
| ----------- | ------------ |
| const canvas = document.querySelector('canvas') | Toma el lienzo del DOM  |
| const c = canvas.getContext('2d') |  Obtiene el contexto para las funciones del canvas 2d | 
| canvas.width = window.innerWidth |  Establecer el ancho del lienzo al ancho de la pantalla. | 
| canvas.height = window.innerHeight |  Establecer la altura completa de la ventana | 

### Dibujar formas básicas

|  | Descripción |
| ----------- | ------------ |
| c.fillRect(x, y, width, height)  | Rectángulos - Rellenos |
| c.strokeRect(x, y, width, height) | Rectángulos - Trazos |
|c.arc(x, y, radius, startAngle, endAngle, drawClockwise) | Círculos |
| | |

### JavaScript Object
```
function Object(x, y, radius, color) { this.x = x  this.y = y
 this.radius = radius
 this.color = color
}
```

Hecho con ❤️ 

Have fun! 🚀
