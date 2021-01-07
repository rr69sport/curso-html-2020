# Elementos de línea

[Inicio](../README.md) [Anterior](k_elementos-de-bloque.md) [Siguiente](k_elementos-de-bloque.md)

Las etiquetas de línea a diferencia de las de bloque, no crean una nueva línea, sino que ocupan sólo el espacio que el contenido les permita ocupar. En general, los elementos en línea pueden contener únicamente los datos y otros elementos en línea. Por tanto no pueden ser contendores de elementos de bloque.

Por ejemplo:

> `<p>Este <strong>strong</strong> es un elemento en línea</p>`

En el navegador se vería así

> Este **strong** es un elemento de linea

## Más utilizados

Enfatizado de texto
| Elemento | Significado |
| :------: | ----------- |
| `<small></small>*` | Menos énfasis que el texto normal |
| `<em></em>*`    | emphasis |
| `<strong></strong>*`| Más énfasis |

> **\*** A nivel visual, el texto que contienen es diferente al texto que está por fuera, eso es porque la etiqueta por si misma le dice al navegador que ese texto que contiene es más o menos importante que el lo rodea, y de manera visual, se le dice al usuario la importancia de ese texto. Si por ejemplo un texto dentro un párrafo, tiene una importancia de 0 para el navegador, la etiqueta `em` dentro de ese párrafo valdría 1, y **strong** valdría 2

Otras
| Elemento | Significado |
| :------: | ----------- |
| `<br>` | Forzar salto de línea |
| `<wbr>` | Salto de línea si hiciera falta |
| `<time></time>` | Le dice al navegador que el contenido es una hora, fecha o ambas |

## En desuso

| Elemento | Significado |
| :------: | ----------- |
| `<i></i>*` | Itálica |
| `<b></b>` | Bold |
| `<u></u>` | Underline |

> **\*** Itálica a día de hoy se usa para representar iconografía en HTML. Por ejemplo un ícono de una red social o el de menú hamburgueza.

[Inicio](../README.md) [Anterior](k_elementos-de-bloque.md) [Siguiente](l_elementos-de-linea.md)
