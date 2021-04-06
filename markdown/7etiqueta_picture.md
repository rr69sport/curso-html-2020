# Etiqueta picture

[Inicio |](README.md) [Anterior |](6atributo_srcset.md) [Siguiente](8etiqueta_audio.md)  


A día de hoy, la etiqueta `picture` es experimental pero ya lo soportan todos los navegadores principales. Funciona como el atributo srcset pero nos da más opciones. Dentro de la etiqueta picture ponemos `source srcset` y las imágenes que necesitemos. Pero atención picture requiere de una imagen de respaldo para funcionar. Es asi, que necesitamos poner un fallback o copia de seguridad de forma obligatoria.


![uso correcto de la etiqueta picture](/assets/picture/picture1.png)


Otra forma es dentro de picture agregar el srcset y agregar el atributo `media` con esto le decimos cuál es el ancho de pantalla en el que queremos que cambie de imagen. Siempre hay que tener una imagen de respaldo para el caso que no cargue webp, así el navegador usará la imagen de seguridad. También en lugar de media poodemos usar dpr.

![picture usando el atributo media](/assets/picture/picture2.png)


---
![youtube logo](assets/logos/youtube_logo_30.png) [Etiqueta Picture](https://youtu.be/WXV-Nv-cOuU)

![github logo](assets/logos/github_logo_30.png) [Curso HTML 2020/2021](https://github.com/DorianDesings/html-2020-2021)  

---

[Inicio |](README.md) [Anterior |](6atributo_srcset.md) [Siguiente](8etiqueta_audio.md)  
