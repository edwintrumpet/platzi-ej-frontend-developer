# Curso de Frontend developer



## Notas

### Índice
- [Referencias del lenguaje](#referencias-del-lenguaje)
- [Proceso de renderizado de la web](#proceso-de-renderizado-de-la-web)
- [Debugging](#debugging)
- [PseudoClases y PseudoElementos](#pseudoclases-y-pseudoelementos)
- [Arquitecturas de CSS](#arquitecturas-de-css)
- [Utilidades](#utilidades)
- [Profundizar](#profundizar)

### Referencias del lenguaje

- [HTML](https://htmlreference.io/ "html reference")
- [CSS](https://cssreference.io/ "css reference")

### Proceso de renderizado de la web

Partes del renderizado

- **Bytes:** Transforma el código a bytes.
- **Characters:** Transforma los bytes a caracteres de acuerdo a la codificación que estemos usando (habitualmente  utf8).
- **Tokens:** Transforma los caracteres en tokens.
- **Nodes:** Transforma los tokens en objetos que ya son entendidos por el navegador.
- **DOM:** Organiza los nodos en una estructura de árbol de acuerdo a la anidación y relaciones que tienen los elementos entre ellos.
- **CSSOM:** Asigna estilos a los nodos y los organiza en un árbol igual que el DOM.

Proceso del renderizado

1. Procesa el HTML y construye el DOM
2. Procesa el CSS y contruye el CSSOM
3. Junta el DOM y el CSSOM para construir el Render Tree
4. Ejecuta el diseño en el Render Tree
5. Pinta el nodo en la pantalla

### Debugging

La [W3C](https://www.w3.org/ "World Wide Web Consortium") que es la entidad encargada de definir los estándares del leguaje tiene una aplicación en la que podemos poner a prueba nuestro código para detectar errores <https://validator.w3.org/>

### Pseudoclases y Pseudoelementos

- **[PseudoClases](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes):** Se caracterizan por anteponer :
- **[PseudoElementos](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements):** Se caracterizan por anteponer ::

### Arquitecturas de CSS

- **[OOCSS](https://www.smashingmagazine.com/2011/12/an-introduction-to-object-oriented-css-oocss/):** (CSS orientado a objetos), Separa el diseño del contenido para hacerlo reutilizable.
- **[BEM](http://getbem.com/introduction/):** (Block element modify), Separa los bloques, los elementos y los modificadores.
- **[SMACSS](http://smacss.com/):** (Arquitectura de CSS escalable y modular), divide los estilos en 5 fases:
    1. Divide el CSS en componentes Base que son los elementos que usaremos en toda la aplicación.
    2. Definimos Layouts que son los elementos que usaremos en la página una sola vez como el footer o el header.
    3. Definimos módulos, que son componentes reutilizables.
    4. Definimos estados, como cambios de estilos en elementos de acuerdo a su interacción con el usuario, con el tiempo o con otros elementos.
    5. Definimos los temas, por ejemplo el modo oscuro o claro de una aplicación.
- **[ITCSS](https://www.xfive.co/blog/itcss-scalable-maintainable-css-architecture/):** (Triángulo invertido de CSS), dividir todos nuestros archivos de CSS en ciertas partes para que no se combinen entre sí.
    - Ajustes
    - Herramientas
    - Genérico
    - Elementos
    - Objetos
    - Componentes
    - Utilidades
- **[Atomic Design](https://bradfrost.com/blog/post/atomic-web-design/):** Separa los estilos y el diseño desde lo más elemental a lo más general.
    - Átomos
    - Moléculas
    - Organismos
    - Templates
    - Páginas

### Utilidades

- [Emojis](https://coolsymbol.com/emojis/emoji-for-copy-and-paste.html "Emoji keyboard")
- [Paletas de colores (Color Hunt)](https://colorhunt.co/ "Color hunt")
- [Paletas de colores (Coolors)](https://coolors.co/001514-fbfffe-6b0504-a3320b-e6af2e "coolors")

### Profundizar

- Arquitecturas de CSS, especialmente BEM, SMACSS y Atomic Design
