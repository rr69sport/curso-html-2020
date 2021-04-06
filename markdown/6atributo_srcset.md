# Atributo srcset

[Inicio |](README.md) [Anterior |](5device_pixel_ratio.md) [Siguiente](7etiqueta_picture.md)  

Veremos como decirle al navegador que cargue una imagen u otra en función del device pixel ratio que indiquemos. Es decir, indicarle al navegador que cargue una portada mobile si tenemos un device pixel ratio más grande que 1 y sino que cargue la normal para desktop.


Crearemos una imagen con tamaño para móvil y así usarla en nuestro ejemplo. En lugar de usar src vamos a utilizar un set de src, usando la etiqueta `srcset`. Agregaremos las imágenes separadas por comas. De tener 2 imágenes sin indicar las condiciones de carga Chrome cargará la primera que encuentre.

Para decirle que cargue una u otra imagen, en función del pixel ratio que tenga debemos darle condiciones de carga. Por ejemplo, si tiene un device pixel ratio de 2 que cargue esa imagen en versión móvil. Este procedimiento, de selección de imágenes de acuerdo a la resolución de pantalla optimiza los tiempos de carga porque también cambia el peso de las imágenes que vamos a mostrar.

En el caso que algún navegador no soporte webp debemos de agregar siempre una copia de respaldo. Para navegadores como internet explorer que no soportan webp ni tampoco srcset es conveniente agregar src en el caso que no pueda cargar nada cargará esta copia de seguridad. Como vemos en el ejemplo nuestras copias de respaldo son las imágenes que tiene formato jpg.


![como usar srcset](/assets/srcset/srcset1.png)


---
![youtube logo](assets/logos/youtube_logo_30.png) [Atributo srcset](https://youtu.be/qj81Y4l2Wvs)

![github logo](assets/logos/github_logo_30.png) [Curso HTML 2020/2021](https://github.com/DorianDesings/html-2020-2021)  

---

[Inicio |](README.md) [Anterior |](5device_pixel_ratio.md) [Siguiente](7etiqueta_picture.md)  
