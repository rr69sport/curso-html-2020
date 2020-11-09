# Etiqueta Main

Es una etiqueta de definición explícita. Definición en la cuál se agrupan también **article, section, header, footer, aside y nav**. Puedes ver esa sección de etiquetas [aquí](h_header-y-footer.md)

Representa el contenido principal de la página. El área principal del contenido consiste en el contenido que está directamente relacionado, o se expande sobre el tema central de un documento. Este contenido debe ser único al documento, excluyendo cualquier contenido que se repita a través de un conjunto de documentos como barras laterales, enlaces de navegación, información de derechos de autor, logos del sitio y formularios de búsqueda (a menos, claro, que la función principal del documento sea un formulario de búsqueda).

Solo puede haber uno por página y debe ser hijo directo de body.

Ejemplo de uso semántico de la etiqueta `main`

```html
<body>
    <header>
        <!-- Aquí puede ir un menú, el logo, redes sociales etc etc. -->
    </header>
    <main>
        <h1>Ejemplo de uso semántico de la etiqueta main</h1>
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
