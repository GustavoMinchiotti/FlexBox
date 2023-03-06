 Flexbox Alura
=================
Partimos de una carpeta provista por el instituto
-------------------
La carpeta fue descargada descomprimida y abierta en VsCode para trabajar. (trajo archivos `desktop.ini` 
que nunca vi en html ni css)

### Preparando el archivo
Creo un archivo CSS exclusivo para flexbox.

Lo primero a modificar será el header, ya que trabajamos en el orden de la página y sus secciones, tomando las clases 
existentes en el html.

**_!no se si lo hace a propósito o está re perdido el profesor da muchas vueltas_**

*! responsive*

*Todos estos cambios se van a aplicar hasta un máximo de 768px luego vuelve al CSS de arriba*

### Al no haber nade realmente nuevo lo aprendido lo comento en el Css directamente.

https://css-tricks.com/snippets/css/a-guide-to-flexbox/   página muy interesante

## felx grow y shrink

The `flex-grow` property specifies how much the item will grow relative to the rest of the flexible items inside the 
same container.

The `flex-shrink` property specifies how the item will shrink relative to the rest of the flexible items inside the 
same container. por ejemplo puedo priorizar algún elemento y reducir los otros en mayor medida.
-------
### ¿Qué propiedades funcionan SOLAMENTE en los flex container y cuáles son las que funcionan en los flex ítems?

La propiedad display: flex puede ser usada en los dos. En caso de que sea utilizada un flex ítem este elemento será tanto 
un flex ítem cuanto un flex container.

Lo mejor es tener en cuenta que lo ideal es, siempre que sea necesario, consultar la documentación a través de este sitio.

Ahí podemos ver claramente qué propiedades se aplican al container y a los flex ítems, no hay que estar memorizando, 
esto vendrá naturalmente con la práctica.

| Clases resumen del curso                  | links                                                                                                                                                                         | 
|-------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Clase Flexbox                             | https://app.aluracursos.com/course/flexbox-posicione-elementos-pantalla/task/77466                                                                                            |
| Propiedad Flex en detalles grow & shrink  | https://app.aluracursos.com/course/flexbox-posicione-elementos-pantalla/task/77468                                                                                            |
| Para practicar JUEGOS en flexbox          | Flexbox Froggy,  Flexbox defense : En los juegos encontrarás otra propiedad llamada align-self. Esta propiedad es aplicada al flex item y hace que se alinee individualmente. |                                               |
| Para casos específicos por ejemplo videos | https://app.aluracursos.com/course/flexbox-posicione-elementos-pantalla/task/77497                                                                                            |
| nota de alura bien explicada              | https://www.aluracursos.com/blog/flexbox-css-guia-completo-elementos-y-ejemplos                                                                                               |


 `flex- basis`, va a funcionar muy parecido a lo que sería un width o height (según si es row o column) pero, dentro 
 de la función **fex box**.

Un atajo para todo esto, es colocar `flex`. Y colocamos 0 para el grow, 1 para shrink, y luego colocamos 25% o 30% por
ejemplo para la largura.

`flex : 0, 1, 30% ;`

---------------

# Layouts responsive

## Introducción al EMMET















.