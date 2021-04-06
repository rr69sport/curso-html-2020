# Device pixel ratio

[Inicio |](README.md) [Anterior |](4insertar_imagenes.md) [Siguiente](6atributo_srcset.md)  

            
El concepto de `Device Pixel Ratio` es algo muy importante cuando se trabaja en desarollo web y sobre todo cuando se trabaja para adaptar una web a un móvil, cuando queremos hacer webs que se vean bien en un móvil lo que se denomina `responsive`.

**DPR (Device Pixel Ratio)**, es la relación que existe entre los pixeles reales que tiene el dispositivo y los pixeles que tenemos disponibles para "pintar" contenido.

DPR = pixeles reales / pixeles disponibles

El viewport es el espacio que tenemos disponible para dibujar. Esta página nos indica la resolución de pantalla que estamos usando, <a target="_blank" href="http://whatismyviewport.com">what is my viewport</a>.

![resolución de pantalla](/assets/device_pixel_ratio/viewport.png)


Como podemos notar la resolución de pantalla es de 1920px por 969px cuando el alto de la pantalla real es de 1080px. Esto significa que nuestro espacio disponible es menor ya que la diferencia se lo toma el navegador. En este caso el DPR que indica es 1.

Ahora veremos como este espacio para dibujar es completamente diferente en móviles. Cuando trabajamos en un móvil nunca es dpr 1, normalmente es 2 o más de 3. Desde el inspector de Chrome vamos a cambiar la pantalla a la resolución de un móvil Motog4 o GalaxyS5. El espacio disponible aqui es de un dpr igual a 3. Esto porque la resolución de pantalla es de 360px por 640px.


![resolución de pantalla de un móvil](/assets/device_pixel_ratio/viewport_mobile.png)


Tomaremos como ejemplo la carga de una imagen con un width de 300px y como se comporta el dpr en el móvil y en el desktop. Recuerda que es un ejemplo, el width no debe ir en el html salvo excepciones.

Cambiando a la resolución del móvil a GalaxyS5 vemos como el dpr es de 3. Podemos ver la imagen con un tamaño fijo de 300px. Si queremos que se adapte al tamaño de la pantalla le daremos desde css un max-width de 100% y quitaremos el tamaño fijo de 300px.

Resolución de pantalla del móvil GalaxyS5, 360px por 640px y un DPR de 3


![dpr3 resolución de pantalla móvil](/assets/device_pixel_ratio/dpr3.png)


Resolución de pantalla de un ipad, 768px por 1024px y un DPR de 2


![dpr2 resolución de pantalla ipad](/assets/device_pixel_ratio/dpr2.png)

Resolución de pantalla desktop, 1440px por 1093px y un DPR de 1

![dpr1 resolución de pantalla desktop](/assets/device_pixel_ratio/dpr1.png)


---
![youtube logo](assets/logos/youtube_logo_30.png) [Device Pixel Ratio](https://youtu.be/hQdPhmEMkNg)

![github logo](assets/logos/github_logo_30.png) [Curso HTML 2020/2021](https://github.com/DorianDesings/html-2020-2021)  

---
[Inicio |](README.md) [Anterior |](4insertar_imagenes.md) [Siguiente](6atributo_srcset.md)