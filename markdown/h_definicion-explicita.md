# Etiqueta Main

## Comunes a las 3 etiquetas

Son etiquetas de bloque, que a nivel semántico tienen una importancia específica.
A nivel de descendientes directos de `<body>`, solo puede haber una etiqueta de cada una como hijo directo. Y ninguna de las 3 debe contener como hijo directo a una etiqueta del mismo nombre, por ejemplo: un `<header>` **NO** puede ser hijo de otro `<header>`.

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
                    <a href="./encabezados.html">Sección anterior</a>
                </li>
                <li>
                    <a href="#">Siguiente sección</a>
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

## Main

Representa el contenido principal del `<body>` de un documento o aplicación. El área principal del contenido consiste en el contenido que está directamente relacionado, o se expande sobre el tema central de un documento o la funcionalidad central de una aplicación. Este contenido debe ser único al documento, excluyendo cualquier contenido que se repita a través de un conjunto de documentos como barras laterales, enlaces de navegación, información de derechos de autor, logos del sitio y formularios de búsqueda (a menos, claro, que la función principal del documento sea un formulario de búsqueda).

Solo puede haber uno por página y debe ser hijo directo de body.

### Ejemplo de `<main>`

```html
<body>
    <header>
        <!-- Aquí puede ir un menú, el logo, redes sociales etc etc. -->
    </header>
    <main>
        <h1>Título principal</h1>
        <p>Una breve descripción.</p>

        <article>
            <h2>Sección importante del tema principal</h2>
            <p>Descripción de esa sección.</p>
            <p>Más texto o información </p>
        </article>

        <article>
            <h2>Otra sección importante de la principal</h2>
            <p>Algún tipo de información.</p>
            <p>Más información relevante </p>
            <p>... </p>
        </article>
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
        <address>
            Autor del curso Dorian Desings
            Canal de YouTube
            <!-- Más información relacionada. -->
        </address>
    </footer>
</body>
```
