# Accesibilidad

[Inicio |](README.md) [Anterior |](14fontawesome.md) [Siguiente](16graph.md)  


Para que conozcáis la base de la accesibilidad haremos una pequeña introducción sobre qué es y para qué sirve. 

El objetivo de la accesibilidad es hacer una página web que sea accesible para todo el mundo, independientemente si pueden ver o no la página. Principalmente esta diseñado para navegadores de terminal o navegadores que leen la página web y la dictan. Es decir, un navegador por voz pensado para personas no videntes, a quienes les va diciendo dónde están y por dónde se van moviendo en la web.

El atributo `tabindex` permite al usuario moverse por la página web indicando un orden. Normalmente se pone en las zonas para navegar por tabulador y de una forma rápida, por ejemplo, saltar de un campo de formulario a otro o de una noticia a otra. 

![uso de tabindex](/assets/accesibilidad/accesibilidad1.png)


Los atributos, `role y aria`, están diseñados para no videntes que usan navegadores por voz. Para entender cómo funcionan los lectores de pantalla podemos instalar desde chrome web store la extensión de [Screen Reader](https://chrome.google.com/webstore/detail/screen-reader/kgejglhpjiefppelpmljglcjbhoiplfn?hl=es).

Al recorrer la página el lector de pantalla nos brinda información sobre la página web. Agregaremos role y aria para cambiar el tipo de información que nos brinda un enlace. Esta información es la que va a leer el lector al usuario. Con aria-label, agregamos la información que queremos que el navegador lea. Y con role, el tipo de elemento en el que nos estamos posicionando.

![uso de role y aria-label](/assets/accesibilidad/accesibilidad2.png)

Aquí os dejo varios enlaces para seguir profundizando en el tema de accesibilidad.

- [Especificación de la W3C](https://www.w3.org/TR/wai-aria-practices-1.1/)
- [Especificación de la MDN](https://developer.mozilla.org/es/docs/Web/Accessibility/ARIA)
- [Documentación de Google](https://developers.google.com/web/fundamentals/accessibility/semantics-aria)
- [Post sobre ARIA](https://www.lullabot.com/articles/what-heck-aria-beginners-guide-aria-accessibility)


---

![youtube logo](assets/logos/youtube_logo_30.png) [Accesibilidad](https://youtu.be/-4y3vb0IHgw)

![github logo](assets/logos/github_logo_30.png) [Curso HTML 2020/2021](https://github.com/DorianDesings/html-2020-2021)  

---

[Inicio |](README.md) [Anterior |](14fontawesome_figure.md) [Siguiente](16graph.md)