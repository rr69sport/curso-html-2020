# Etiquetas de definición explícita. Parte final

[Inicio](../README.md) [Anterior](i_article-y-section.md) [Siguiente](k_elementos-de-bloque.md)

## Aside

Se utiliza para representar contenido indirectamente relacionado pero que no forma parte del contenido principal. Estas secciones son a menudo representadas como barras laterales o como inserciones y contienen una explicación al margen como una definición de glosario, elementos relacionados indirectamente, como publicidad, la biografía del autor, o en aplicaciones web, la información de perfil o enlaces a blogs relacionados.

Semánticamente hablando, tanto la [W3C](https://www.w3.org/TR/2011/WD-html5-author-20110809/the-aside-element.html), como la [MDN](https://developer.mozilla.org/es/docs/Web/HTML/Elemento/aside), aceptan que puede ir anidado dentro de la etiqueta `main` como por fuera. También cabe destacar que puede haber más de una aside por página.

Ejemplo de uso semántico de una etiqueta Aside

```html
<body>
    <header>
        <!-- Puede ir menú de navegación, redes sociales -->
        <!-- También puede ir un logo, formulario de búsqueda, etc -->
    </header>
    <aside>
        <p>Aquí iría por ejemplo, links a películas basadas en comics.</p>
    </aside>
    <main>
        <header>
            <!-- Sobre lo que trata el tema principal de la página -->
            <!-- por ejemplo -->
            <h1>Películas de terror</h1>
        </header>
        <article>
            <!-- Un artículo sobre una película de terror -->
            <!-- por ejemplo -->
            <header>
                <h2>Freddy Krueger</h2>
            </header>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
        </article>
        <article>
            <!-- Otra película de terror -->
            <header>
                <h2>Viernes 13</h2>
            </header>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
        </article>
    </main>
    <footer>
        <p>Información relacionada a los artículos principales, como link de recursos. Los autores, etc, etc.</p>
    </footer>
</body>
```

[Inicio](../README.md) [Anterior](i_article-y-section.md) [Siguiente](k_elementos-de-bloque.md)
