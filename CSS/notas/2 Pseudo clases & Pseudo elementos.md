¿Qué son? 🤔
Dentro del css, se podrían categorizar como selectores, nos permiten:

Acceder a elementos que los selectores básicos no nos permiten acceder.
Permiten aplicar estilos a elementos no solo en función del DOM, sino también a factores externos como el historial de visitas. (tener en cuenta la pseudo clase :visited).
Pseudo Elementos ::
Los Pseudo-elementos se utilizan para seleccionar una parte de alguna estructura HTML, por ejemplo:

p::first-letter Selecciona la primera letra de un párrafo (No solamente de un párrafo.
elemento:beforeCrear un elementos antes del contenido del elementohtml con afterse crear después del contenido.
Pseudo Clases :
Las Pseudo-clases se utilizan para seleccionar un elemento en un determinado estado, por ejemplo:

:active Estado que se activa cuando el puntero del mouse pasa por encima del elemento.
:focus pseudo-clase activada cuando un campo de formulario o elemento html tiene el foco del mouse (esta seleccionado o se este escribiendo en dicho elemento)
Lista de Pseudo - clases - elementos 😉
Pseudo Elementos ::
::after
::before
::first-letter
::first-line
::selection
::backdrop
Pseudo Clases :
:active
:checked
:default
:dir()
:disabled
:empty
:enabled
:first
:first-child
:first-of-type
:fullscreen
:focus
:hover
:indeterminate
:in-range
:invalid
:lang()
:last-child
:last-of-type
:left
:link
:not()
:nth-child()
:nth-last-child()
:nth-last-of-type()
:nth-of-type()
:only-child
:only-of-type
:optional
:out-of-range
:read-only
:read-write
:required
:right
:root
:scope (en-US)
:target
:valid
:visited







¿Qué es BEM?
Es una metodología que nos ayuda como desarrolladores a facilitar la tarea de rear nombres de clases mediante convenciones prácticas.

B significa Bloque o Block (para los cuates) y un bloque es un pedazo de nuestra página web que tiene sentido por sí mismo, es decir, que es una sección independiente en una página web.

E significa Elemento o Element (para que práctiques tu inglés) y los elementos son las distintas partes que conforman un bloque. A diferencia de los bloques, los elementos no tienen significado por sí mismos ni son independientes.

M significa Modificador o Modifier (aportaciones de BEM e inglés c:), y estos son indicadores que colocamos a nuestros bloques o elementos para para poder diferenciar una variante de un bloque o elemento para poder modificar su estilo o comportamiento.

Ejemplos:

Un bloque puede ser un menú de navegación. Si lo pensamos, un menu de navegación funciona por sí mismo en una página web y es una sección independiente.
En este mismo ejemplo del menú de navegación, un elemento puede ser cada uno de los enlaces que componen nuestro menú de navegación.
Siguiendo esta misma línea, un modificador puede ser cuando estamos hacemos hover o activamos alguno de esos enlaces.
¿Cómo declaro los nombres de clases con esta metodología?
Simple, recuerda que quiere decir BEM:
bloque
bloque__elemento
bloque__elemento–modificador