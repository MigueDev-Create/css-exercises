# Un estilo de 'modal' habitual
Este es otro patrón muy común en la web. La solución es _sencilla_... pero puede que no te resulte evidente al principio. Tendrás que editar un poco el HTML para colocar todo donde debe ir.

### Una pista
Según cómo lo enfoques, puede que necesites repasar la propiedad `flex-shrink` para evitar que un elemento flex quede aplastado. Además, presta atención a la estructura del html: en concreto, plantéate añadir un contenedor adicional que rodee los divs de la cabecera, el botón, el texto principal, cancelar y continuar; y plantéate mover el div de la cabecera para que abarque también el botón.

## Resultado deseado

![resultado deseado](./desired-outcome.png)

### Autocomprobación

- El icono azul está alineado a la izquierda.
- Hay el mismo espacio a ambos lados del icono (los huecos entre el icono y el borde de la tarjeta, y entre el icono y el texto, son iguales).
- Hay padding alrededor del borde del modal.
- La cabecera, el texto y los botones están alineados entre sí.
- La cabecera está en negrita y con un tamaño de texto algo mayor que el del texto.
- El botón de cerrar está alineado verticalmente con la cabecera y situado en la esquina superior derecha de la tarjeta.
