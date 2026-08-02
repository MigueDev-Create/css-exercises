# Encadenar selectores

Los créditos de las imágenes de este ejercicio son para [Katho Mutodo](https://linktr.ee/photobykatho_) y [Andrea Piacquadio](https://www.pexels.com/@olly?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels).


En este ejercicio te proporcionamos un archivo HTML completo y un archivo CSS con los que trabajar. El propósito es centrarse en entender cómo encadenar distintos selectores, en lugar de limitarse a añadir atributos.

Tenemos dos imágenes a las que dar estilo, cada una con dos nombres de clase, de los cuales uno es compartido. El objetivo aquí es encadenar los selectores de ambos elementos, de forma que cada uno tenga aplicado un estilo único a pesar de usar un selector de clase compartido. Por ejemplo, quieres que un elemento que tiene tanto X como Y tenga un conjunto de estilos, mientras que un elemento con X y Z tenga un conjunto de estilos completamente distinto. Hemos incluido también las imágenes originales para que puedas comparar cómo quedan los estilos que vas a añadir, así que no les añadas ningún estilo.

Las propiedades que debes añadir a cada elemento son:

- Haz que el elemento que tiene las clases `avatar` y `proportioned` mida 300 píxeles de ancho. Queremos que conserve automáticamente sus proporciones cuadradas originales, así que no fijes un valor en píxeles para su altura.
- Haz que el elemento que tiene las clases `avatar` y `distorted` mida 200 píxeles de ancho, y después haz que su altura sea el doble que su anchura (aquí sí debes fijar un valor en píxeles).

## Resultado deseado
![resultado deseado](./desired-outcome.png)

### Autocomprobación
- ¿Encadenaste correctamente los selectores de clase en cada regla?
- ¿Conserva la imagen `proportioned` sus proporciones cuadradas originales?
- ¿La imagen `distorted` acaba viéndose aplastada y, bueno, distorsionada?
