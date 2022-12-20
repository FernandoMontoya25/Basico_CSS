# Introduccion a CSS
> # Indice
> 1. Modelo de caja
> 2. Flex-box
> 3. Display Grid
> 4. Etiquetas y sus usos.

> # 1. Modelo de caja
- **Margin:** Es la separacion que va a tener nuestro contenedo con respecto al demas contenido.
- **Border:** Es la propiedad que le da un bordeado en las esquinas a nuestros contenedores.
- **Padding:** Es la separacion que va a tener el contenido dentro del contenedor pero esta separacion estara dentro del mismo no fuera.
- **width:** Es la dimencion de largo que van a tener nuestros contenedores.
- **height:** Es la dimencion de altura que van a tener nuestros contenedores.

![image](https://user-images.githubusercontent.com/66334502/208677952-f2122f38-69e6-478a-a5c4-a42fb01580f1.png)

> # 2. Flex-box

> # 3. Display Grid

> # 4. Etiquetas y sus usos
```css
/*background: Establece todas las propiedades de estilo de fondo a la vez, como el color, la imagen, el origen y el tamaño o el metodo de repeticion*/

background-color: red;

/*Hover: Etiqueta que proporciona diseño cuando el cursor pasa sobre el contenido*/

.numero:hover{
    cursor: pointer;
    background-color: blue;
}

/*active: Representa un elemento como un boton, por lo general se activa cuando el usuario preciona el boton principal del mouse*/

.numero:active{
    background-color: yellow;
}
```
> # 5. Tipos de display (Inline, block y inline-block)

- **Display block:** Es una propiedad de CSS que hace que un elemento se muestre como un bloque, ocupando todo el ancho disponible y separandose del contenido que lo rodea (por encima y por debajo).
- **Display inline:** Es una propiedad de CSS que hace que un elemento se muestre en linea, ocupando solo el espacio necesario para mostrar el contenido. Esto significa que el elemento se muestra en linea con los demas elementos, sin separarse por encima o por debajo.
- **Display inline-block:** Es una combinacion de los dos anteriores ya que le permite al elemnto mostrado en linea con los demas elementos ( como si fuera un elemento inline) pero tomara el ancho de su contenido (como un elemento block).
- ### Uso: Se usa dentro del div al que queremos aplicarlo no a su contenedor.
![image](https://user-images.githubusercontent.com/66334502/208765406-cb82295f-56b6-473b-b75a-38352f6db7c4.png)

> # 6. Propiedades basicas para dar Estilo a texto

- **font-family:** esta propiedad define la familia de fuentes que se utilizará para el texto. 
- **font-style:** esta propiedad define el estilo de la fuente (normal, italic, oblicuo, etc.).
- **font-size:** esta propiedad define el tamaño de la fuente.
- **font-weight:** esta propiedad define el grosor de la fuente.
- **color:** esta propiedad define el color del texto.
- **text-decoration:** esta propiedad define la decoración del texto (subrayado, tachado, etc.).
- **text-align:** esta propiedad define la alineación del texto (izquierda, derecha, centrado, etc.).
- **line-height:** esta propiedad define la altura de línea de un documento.

> # 7. Caracteristicas de Position

- **Static:** Posicion por defecto de los elementos, conservan la posicion y espacio donde fueron creados.
- **Absolute:** Permanecen en la posicion de donde fueron creados pero pierden su espacio fisico se sobreponen a los elementos que ocupan dicho espacio.
- **Relative:** Conservan su posicion original y espacio fisico pero se los puede posicionar mediante las propiedades top, right, bottom y left in perder dicho espacio fisico.
- **Fixed:** Pierden su espacio fisico y permanecen de forma fija y siguen el scroll se colocan al lado izquierdo del viewport se los puede posicionar mediante las propiedades top, right, bottom y left.
- **Sticky:** Conservan su espacio fisico pero cuando el scroll los alcanza lo siguen sin perder dicho espacio fisico es muy usado para barras de navegacion y se los puede posicionar con las propiedades top, right, bottom y left.
















