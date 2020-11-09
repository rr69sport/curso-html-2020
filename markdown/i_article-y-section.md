# Article y Section

## `<section>`

Es un contenedor genérico que agrupa contenido que está relacionado. Cuando creamos bloques cuyo contenido es parte de un bloqueo mayor, usamos `<section>`
> **Importante:**
> No se debe usar el elemento `<section>` como un mero contenedor genérico; para esto ya existe `<div>`, especialmente si el objetivo solamente es aplicar un estilo (CSS) a la sección. Como regla general, el título de una sección debería aparecer en el esquema del documento.

## `<article>`

Es un contenedor que representa contenido independiente, es decir, podemos leer ese fragmento en cualquier otro sitio y tendrá sentido por sí mismo. Al ser contenido independiente y con sentido po sí mismo, implica que pueda tener un `<header>` y `<footer>` propios.

## Anidamiento

*¿Cuál es la forma de anidación correcta para `<article>` y `<section>`?*
La respuesta es que un `<article>` puede contener elementos `<section>` y un `<section>` puede contener elementos `<article>`.

### Ejemplo de `<section>` anidando `<article>`

```html
<main>
    <header>
        <h1>Agrupación de contenido en HTML</h1>
    </header>
    <section>
        <h2>Etiquetas a nivel de bloque</h2>
        <article>
            <header>
                <h3>Etiqueta article</h3>
            </header>
            <p>
                Es un contenedor que representa contenido independiente, es decir,
                podemos leer ese fragmento en cualquier otro sitio y tendrá sentido por sí mismo.
                Al ser contenido independiente y con sentido po sí mismo,
                implica que pueda tener un <header> y <footer> propios.
            </p>
            <footer>
                <!-- Aquí puede ir de donde se extrajo el artículo por ejemplo -->
            </footer>
        </article>
        <article>
            <header>
                <h3>Etiqueta section</h3>
            </header>
            <p>
                Es un contenedor genérico que agrupa contenido que está relacionado.
                Cuando creamos bloques cuyo contenido es parte de un bloqueo mayor, usamos <section>
            </p>
            <p>
                <strong>Importante:</strong>
                No se debe usar el elemento <section> como un mero contenedor genérico; para esto ya existe <div>,
                especialmente si el objetivo solamente es aplicar un estilo (CSS) a la sección.
            </p>
            <p>Como regla general, el título de una sección debería aparecer en el esquema del documento.</p>
            <footer>
                <!-- Aquí puede ir de donde se extrajo el artículo por ejemplo -->
            </footer>
        </article>
    </section>
    <footer>
        <!-- Información sobre fecha de publicación de los artículos por ejemplo -->
    </footer>
</main>
```

Como puedes ver, cada artículo tiene sentido por sí solo, y si estuviera en cualquier otro sitio, seguiría teniendo sentido. La etiqueta `<section>` los anida formando un bloque mayor que en este caso es "Etiquetas a nivel de bloque"

### Ejemplo de `<article>` anidando `<section>`

```html
<main>
    <article>
        <header>
            <h1>Navegadores más usados en 2020</h1>
        </header>
        <section>
            <header>
                <h3>Chrome</h3>
            </header>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolor a tenetur autem aperiam.
                Dignissimos est facilis iusto, vitae, nam ducimus hic?
                Magni necessitatibus dignissimos ex sit? Dolorum qui harum laborum.
            </p>
            <footer>
                <!-- Aquí puede ir de donde se extrajo el artículo por ejemplo -->
            </footer>
        </section>
        <section>
            <header>
                <h3>Forefox</h3>
            </header>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolor a tenetur autem aperiam.
                Dignissimos est facilis iusto, vitae, nam ducimus hic?
                Magni necessitatibus dignissimos ex sit? Dolorum qui harum laborum.
            </p>
            <footer>
                <!-- Aquí puede ir de donde se extrajo el artículo por ejemplo -->
            </footer>
        </section>
    </article>
    <footer>
        <!-- Información sobre fecha de publicación de los artículos por ejemplo -->
    </footer>
</main>
```

Aquí cada sección es un navegador distinto pero los dos pertencen al mismo artículo.

[Inicio](../README.md) [Anterior](h_header-y-footer.md) [Siguiente](i_article-y-section.md)
