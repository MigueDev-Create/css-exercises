# El Santo Grial de la maquetación

En este último ejercicio de flexbox vas a recrear una maquetación de sitio web increíblemente común. Es tan común que a menudo se la llama la maquetación [Holy Grail](https://www.google.com/search?q=holy+grail+layout&tbm=isch&sclient=img) (el Santo Grial)... y con flexbox es en realidad bastante fácil de conseguir.

Como en el ejercicio anterior, te hemos dejado algo más de trabajo por hacer.

### Pistas
- Necesitarás cambiar el flex-direction para empujar el pie de página hacia abajo.
- Necesitarás añadir algunos divs como contenedores para que las cosas se alineen correctamente.
- `flex-wrap` te ayudará a alinear bien las tarjetas.
- Asegúrate de definir cuánto espacio deben ocupar las tarjetas para que `flex-wrap` funcione como se espera.

## Resultado deseado

![resultado deseado](./desired-outcome.png)

El número de tarjetas alineadas en esa sección cambiará según el ancho de tu pantalla, así que no te agobies por conseguir _exactamente_ una cuadrícula de 2x3 o 3x2.

En una pantalla más pequeña se verá así:

![más pequeño](./desired-outcome-smaller.png)

Nota: los emojis pueden aparecer como uno o varios símbolos de texto (p. ej. &#9734;&#9794;) si no tienes instalada en tu sistema operativo una familia de fuentes con emojis. Esto no afecta al ejercicio y puedes ignorarlo.

### Autocomprobación
- El texto de la cabecera tiene un tamaño de 32px y un grosor de 900.
- El texto de la cabecera está centrado verticalmente y a 16px del borde de la pantalla.
- El pie de página está empujado a la parte inferior de la pantalla (puede quedar _por debajo_ del borde inferior si el contenido de la sección de 'cards' se desborda y/o si tu pantalla es más baja).
- El texto del pie de página está centrado horizontal y verticalmente.
- La barra lateral y las tarjetas ocupan todo el espacio disponible por encima del pie de página.
- La barra lateral mide 300px de ancho (y no se encoge).
- Los enlaces de la barra lateral son de 24px, blancos y no tienen la decoración de subrayado.
- La barra lateral tiene 16px de padding.
- Hay 48px de padding alrededor de la sección de 'cards'.
- Las tarjetas están dispuestas horizontalmente, pero pasan a varias líneas cuando se quedan sin sitio en la página.
