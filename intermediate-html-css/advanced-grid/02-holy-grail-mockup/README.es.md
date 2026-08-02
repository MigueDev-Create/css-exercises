# Maqueta del Holy Grail con Grid

Ahora que has hecho responsive tu Holy Grail Layout, vamos a divertirnos complicándolo un poco y añadiendo algunas características. Puede que esto te resulte algo más desafiante de lo que esperabas. Incluso puede que te tiente usar Flexbox. Pero, por el bien de esta práctica, intenta ver si consigues recrear toda esta maqueta usando solo Grid. ¡Siéntete libre de añadir tu propio contenido de relleno o tus propios estilos también!

### Pistas
- En este ejercicio necesitarás añadir algunos bloques de declaraciones CSS al archivo style.css. Repasa el HTML para ver qué selectores y combinadores puedes usar.
- Aborda la maquetación sección a sección
- No necesitas añadir ni cambiar nada en el HTML, pero te será útil repasar las relaciones entre elementos padre e hijo
- Igual que con Flexbox, puedes centrar fácilmente un elemento convirtiéndolo en una cuadrícula
- No te preocupes por que el elemento de imagen de marcador de posición se estire al redimensionar la ventana del navegador. Eso se verá en las lecciones de Responsive

## Resultado deseado

![resultado deseado](./desired-outcome.png)

Si usas las herramientas de la lección de Advanced Grid Properties, deberías poder conseguir que tus tarjetas de artículo se ajusten automáticamente a medida que se ajusta la ventana del navegador:

![resultado deseado estirado](./desired-outcome-stretched.png)

### Autocomprobación
- El elemento contenedor tiene dos columnas
- La segunda columna del contenedor es 4 veces más grande que la primera
- El elemento contenedor tiene un gap de 4px
- El elemento header tiene dos columnas
- El `ul` dentro del elemento menu contiene otra cuadrícula
- El `ul` dentro del elemento nav contiene otra cuadrícula
- El elemento sidebar tiene un gap de 50px
- Los elementos de texto de la sidebar están centrados con grid
- El elemento article debe definir las columnas de la cuadrícula usando `repeat` junto con las propiedades `auto-fit` y `minmax`
- Las columnas del article deben tener un valor mínimo de 250px y un máximo de 1fr
- El elemento article tiene un gap de 15px
- Los elementos card dentro del contenedor article tienen una altura de 200px
- El header y el footer abarcan ambas columnas
- La sidebar abarca solo la primera columna
- Los elementos nav y article abarcan solo la segunda columna
