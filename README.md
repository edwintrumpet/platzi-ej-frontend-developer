# Curso de Frontend developer



## Notas

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
