# Etiquetas de definición explícita. Parte I

[Inicio](../README.md) [Anterior](g_etiqueta-main.md) [Siguiente](i_article-y-section.md)

¿Cuáles son éstas etiquetas?

Estas etiquetas son: [main](g_etiqueta-main.md), article, section, header, footer, aside y nav

Son etiquetas de bloque, que a nivel semántico tienen un significado específico. Tienen una definicón explícita sobre el contenido que agrupan.

## Header y Footer

A nivel de descendientes directos de body, solo puede haber **una etiqueta header y una etiqueta footer como hijo directo**. Y ninguna de las 2 debe anidar una etiqueta del mismo nombre, por ejemplo: un header **no** puede ser hijo de otro header.

## Header

Puede contener algunos elementos de encabezado, así como también un logo, un formulario de búsqueda, un nombre de autor y otros componentes como redes sociales o menú de navegación.

### Ejemplo de `<header>`

```html
<body>
    <header>
        <nav>
            <ul>
                <li>
                    <a href="./">Inicio</a>
                </li>
                <li>
                    <a href="#">Sección anterior</a>
                </li>
                <li>
                    <a href="#">Sección siguiente</a>
                </li>
            </ul>
        </nav>

        <form >
            <fieldset>
                <input type="text" placeholder="Buscar">
                <button type="submit">Buscar</button>
            </fieldset>
        </form>
    </header>

    <main>
        <!-- Aquí va el contenido principal de todo el documento. -->
    </main>

    <footer>
        <!-- Aquí puede ir información acerca del autor de la sección, 
        datos de derechos de autor o enlaces a documentos relacionados. -->
    </footer>
</body>
```

## Footer

Representa un pie de página para el contenido de sección más cercano o el elemento del que desciende, por ejemplo: `<article>, <aside>, <section>, <blockquote>, <details>, <fieldset>, <figure>, <td>`. Un pie de página típicamente contiene información acerca de el autor de la sección, datos de derechos de autor o enlaces a documentos relacionados.</p>
Al igual que `<header>` **NO** debe tener como descendiente otro elemento `<footer>` o `<header>`.

```html
<body>
    <header>
        <!-- Aquí puede ir un menú, el logo, redes sociales etc etc. -->
    </header>
    <main>
        <!-- Aquí va el contenido principal de todo el documento. -->
    </main>
    <footer>
        <p>El curso lo dicta <a href="https://www.youtube.com/channel/UCzuwt7Pi_VB8cP5q5UE4u-A">

        Dorian Desings (Canal de YouTube)</a>, y tiene la validación de la <a href="https://validator.w3.org">W3C</a>.

        El curso se basa en la documentación brindada por la

        <a href="https://developer.mozilla.org/es/docs/Sections_and_Outlines_of_an_HTML5_document">MDN</a>.</p>
    </footer>
</body>
```

[Inicio](../README.md) [Anterior](g_etiqueta-main.md) [Siguiente](i_article-y-section.md)
