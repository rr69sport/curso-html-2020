# Atributo srcset

[Inicio |]() [Anterior |](3device_pixel_ratio.md) [Siguiente](5etiqueta_picture.md)  

Como decirle al navegador que cargue una imagen u otra en función del device pixel ratio.

Creo imágenes para versión móvil de 300px x 168 de 1147 x 642

Decirle al navegador que cargue portada mobile si tenemos un device pixel ratio más grande de 1 y sino que cargue la normal



creo img y en el lugar de usar src usamos srcset un set de imágenes.
separado por comas le decimos que cargue la otra portada mobile

nota chrome carga la primera imagen que encuentra.

dar condiciones para que cargue un u otra
Para decirle que cargue una u otra, en función del pixel ratio
después del enlace de la imagen  
si tiene un device pixel ratio de 3 que cargue esa imagen

inspeccionar, network subbo a 300 y ahi se ve que carga la otra imagen

optimizar código

peso de la imagen
la web carga más rápido

en el caso que no soporte webp 

Para navegadores como internet explorer que no soportan webp ni tampoco srcset es conveniente agregar src en el caso que no pueda cargar nada carga esta. copia de seguridad para que cargue algo



---
![youtube logo](assets/youtube_logo_30.png) [Atributo srcset](https://youtu.be/qj81Y4l2Wvs)

![github logo](assets/github_logo_30.png) [Curso HTML 2020/2021](https://github.com/DorianDesings/html-2020-2021)  

---

[Inicio |]() [Anterior |](3device_pixel_ratio.md) [Siguiente](5etiqueta_picture.md)  
