# Video de referencia

<iframe width="560" height="315" src="https://www.youtube.com/embed/oWmOqxIanjk?si=5-d7lzG1Y7dDdOUq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<ul></ul>
El elemento ul define una lista desordenada. El elemento contiene uno o más elementos li que especifican los ítems de la lista. Por el contrario, el elemento ol define una lista ordenada. El elemento contiene uno o más elementos li que especifican los ítems de la lista como una secuencia ordenada.

<li></li>
Las etiquetas OL y LI nos sirven para crear listas, OL para listas ordenadas y UL para listas sin orden. Dentro de las listas, los elementos se identifican con la etiqueta LI.

<i class=""> </i>
El atributo class en el elemento <i> se utiliza para asignar una o más clases CSS al elemento. En este caso ("fas fas fa-search")se está utilizando una clase de la biblioteca Font Awesome, que es una biblioteca de iconos vectoriales populares. La clase "fas fa-search" se utiliza para representar un icono de búsqueda en la página web. "fas fa-cart-plus" representa un carrito de compras con un signo de suma. Este icono se utiliza comúnmente para indicar la acción de agregar un artículo al carrito de compras en una tienda en línea o en un sistema de comercio electrónico. La clase "fas fa-bars" representa un conjunto de barras horizontales, comúnmente utilizado para indicar un menú o una lista de opciones en un sitio web. La clase fas fa-star representa una estrellas

EN CSS:

El elemento HTML <nav> representa una sección de una página cuyo propósito es proporcionar enlaces de navegación, ya sea dentro del documento actual o a otros documentos.

z-index: 
El atributo z-index te permite ajustar el orden de las capas de los objetos cuando el contenido está siendo renderizado. En CSS 2.1, cada caja tiene una posición en tres dimensiones. Adicionalmente a sus posiciones horizontales y verticales, las cajas caen a lo largo de un "eje-z" y son formadas una encima de la otra.

hover:
La pseudo-clase :hover de CSS coincide cuando el usuario interactúa con un elemento con un dispositivo señalador, pero no necesariamente lo activa. Generalmente se activa cuando el usuario se desplaza sobre un elemento con el cursor (puntero del mouse).

overflow:
La propiedad CSS overflow especifica: si recortar contenido, dibujar barras de desplazamiento o mostrar el contenido excedente en un elemento a nivel de bloque. Usando la propiedad overflow con un valor distinto a visible , valor por defecto, creará un nuevo contexto de formatos de bloques (en-US).
La propiedad overflow es el modo como tomas el control del desbordamiento de un elemento y le dices al navegador cómo desea que se comporte. El valor predeterminado para la propiedad overflow es visible, por lo que, de forma predeterminada vamos a poder ver cuándo se desborda nuestro contenido.

Si deseas cortar el contenido cuando se desborda, puedes establecer el valor overflow: hidden en tu caja, que hace exactamente lo que dice: ocultar el desbordamiento. Esto puede hacer que las cosas desaparezcan, por lo que solo debes utilizar esta opción si ocultar contenido no te va a causar ningún problema.

Position: relative;
Position: absolute;
En position: relative , el elemento está posicionado Relativo a sí mismo. Sin embargo, un elemento absolutamente posicionado es relativo a su padre. Un elemento con position: absolute se elimina del flujo normal de documentos. Se posiciona automáticamente en el punto de inicio (top-left esquina) de su elemento padre

padding;
El padding en CSS es una propiedad o relleno que se crea alrededor del contenido de un elemento dentro de los bordes definidos y sirve para dar formato y diseño a una página web.

margin:
Resumen. La propiedad CSS margin establece el margen para los cuatro lados. Es una abreviación para evitar tener que establecer cada lado por separado con las otras propiedades de margen: margin-top (en-US), margin-right , margin-bottom y margin-left (en-US). También se permiten valores negativos.


@media screen and (max-width:1250) {
    nav{
        margin-bottom: 2em;
    }

    .body {
        grid-template-columns: 1fr;
        text-align: center;
    }

    header::before {
        display: none;
    }

    header{
        height: initial;
    }

    .body > div:nth-child(2) {
        justify-content: center;
        margin: 3em 0;
    }
    .body img{
        transform: none;
    }

    .body p{
        margin: 2em auto 3em auto;
    }
}


Este código CSS es un ejemplo de un bloque @media query. Estas queries se utilizan para aplicar estilos CSS específicos cuando se cumplen ciertas condiciones, como el tamaño de la pantalla del dispositivo.

En este caso particular, el bloque @media screen and (max-width:1250px) se aplica cuando el ancho de la pantalla es de 1250 píxeles o menos. Veamos qué hace cada parte del código dentro de este bloque:

nav { margin-bottom: 2em; }: Esto establece un margen inferior de 2em para todos los elementos <nav> cuando el ancho de la pantalla es de 1250 píxeles o menos.

.body { grid-template-columns: 1fr; text-align: center; }: Para cualquier elemento con la clase .body, cambia la estructura de las columnas del grid a una sola columna (1fr) y ajusta el texto al centro.

header::before { display: none; }: Oculta cualquier contenido antes del elemento <header>. Esto podría ser usado para ocultar un pseudo-elemento específico.

header { height: initial; }: Establece la altura del elemento <header> a su valor inicial. Esto anula cualquier altura específica que se haya establecido anteriormente.

.body > div:nth-child(2) { justify-content: center; margin: 3em 0; }: Para el segundo hijo directo de cualquier elemento con la clase .body, centra su contenido horizontalmente y aplica un margen de 3em arriba y abajo.

.body img { transform: none; }: Para cualquier imagen dentro de un elemento con la clase .body, elimina cualquier transformación que pueda haber sido aplicada previamente.

.body p { margin: 2em auto 3em auto; }: Para cualquier párrafo dentro de un elemento con la clase .body, aplica un margen de 2em arriba y abajo, y 3em a la izquierda y derecha.

En resumen, este bloque de código CSS dentro de @media screen and (max-width:1250px) está diseñado para ajustar el diseño y estilo de ciertos elementos HTML cuando la pantalla es de 1250 píxeles o menos de ancho. Esto se hace para mejorar la experiencia de visualización en dispositivos con pantallas más pequeñas, como tablets o teléfonos móviles, haciendo que la disposición de los elementos y el espacio en pantalla sea más apropiado para estas dimensiones.
