# Encabezados

[Inicio](../README.md) [Anterior](e_estructura.md) [Siguiente](g_etiqueta-main.md)

Los elementos de **encabezado** implementan seis niveles de encabezado del documento. `<h1>` es el más importante, y `<h6>`el menos importante. Un encabezado describe de forma breve el tema de la sección que representa.

> **Importante**
>
> * Los encabezados tienen una representación semántica y NO se deben usar niveles inferiores para reducir el tamaño de la fuente, use la propiedad CSS `font-size` para eso.
>
> * Es semánticamente correcto iniciar por `<h1>`, después use un `<h2>` y así sucesivamente.
>
> * Con el elemento `<section>`, es recomendable evitar usar más de un `<h1>` en una página, Cuando se usan secciones, se debería usar un `<h1>` por sección.

## Estructura correcta de uso de encabezados

Las etiquetas de cabecera pueden generar sub-secciones implícitas en un mismo documento, esto significa que un `h2` es una sub-sección del `h1` que lo antecede y así sucesivamente. Esto beneficia la organización de la información y también ayuda a los usuarios de lectores de pantalla a conocer la jerarquía de los contenidos.

1. `h1` Harry Potter - Título principal o sección general
    1. `h2` Sinoposis - (1)
    2. `h2` Novelas - (1)
       1. `h3` Harry Potter y la Piedra Filosofal - (2)
       2. `h3` Harry Potter y la Cámara de los Secretos - (2)
       3. `h3` Harry Potter y el Prisionero de Azkaban - (2)
       4. `h3` Harry Potter y el Cáliz de Fuego - (2)
       5. `h3` Harry Potter y la Orden del Fenix - (2)
       6. `h3` Harry Potter y el Príncipe Mestizo - (2)
       7. `h3` Harry Potter y las Reliquias de la Muerte - (2)
    3. `h2` Películas - (1)
       1. `h3` Harry Potter y la Piedra Filosofal - (2)
       2. `h3` Harry Potter y la Cámara de los Secretos - (2)
       3. `h3` Harry Potter y el Prisionero de Azkaban - (2)
       4. `h3` Harry Potter y el Cáliz de Fuego - (2)
       5. `h3` Harry Potter y la Orden del Fenix - (2)
       6. `h3` Harry Potter y el Príncipe Mestizo - (2)
       7. `h3` Harry Potter y las Reliquias de la Muerte (Parte 1) - (2)
       8. `h3` Harry Potter y las Reliquias de la Muerte (Parte 2) - (2)

(1) - Tienen el mismo peso o significado porque son secciones principales dentro de la sección general.

(2) - Representa que el contenido es parte del `h2` que lo antecede.

El punto (2) es válido para los `<h4> <h5> y <h6>`, siempre y cuando se mantenga el nivel jerárquico. Un `h6` desciende de un `h5` que a su vez desciende de un `h4` y así sucesivamente.

> Extraído de [developer.mozilla.org](https://developer.mozilla.org/es/docs/Web/HTML/Elemento/Elementos_títulos)

[Inicio](../README.md) [Anterior](e_estructura.md) [Siguiente](g_etiqueta-main.md)
