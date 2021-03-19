# Insertar imágenes

[Inicio |]() [Anterior |](1contenido_embebido.md) [Siguiente](3device_pixel_ratio.md)

Para agregar imágenes a nuestra web necesitamos la etiqueta `<img>` y el atributo `src` para indicar la ruta donde se encuentra nuestra imagen. 

También contamos con el atributo `alt` para agregar una descripción de la imagen. Es obligatorio para el caso que no cargue la imagen y para cuando los usuarios no videntes hacen uso del lector de pantalla.

>Si ingresamos código al validador de la [W3c](https://validator.w3.org/#validate_by_input) y no hemos agregado el atributo alt de seguro el validador nos dará un error.

Para el ejemplo podemos descargar svg gratuitos de [Flaticon](https://www.flaticon.com/) o imágenes gratuitas desde [Pexels](https://www.pexels.com/es-es/).

Agregaremos varios tipos de imágenes como ejemplo del uso de `<img>`  

```html
<img src="/assets/nala.png" alt="Nala">

<img src="/assets/Pikachu.gif" alt="Pikachu bailando">

<img src="/assets/portada.jpg" alt="Portada DorianDesings">
```

En el caso de querer sólo modificar el tamaño de la imagen podemos hacerlo desde css modificando la propiedad width (ancho) de la imagen.

Si sólo mostraremos la imagen lo agregaremos directamente por nombre de la siguiente manera:

```html
<img src="/assets/733547.svg" alt="logo de Facebook">
```  

Si modificaremos la imagen en tiempo real, ya sea para cambiar sus colores o animar la imagen, necesitamos ponerlo de esta forma, agregando todo el código del svg:

```html
<?xml version="1.0" encoding="iso-8859-1"?>
<!-- Generator: Adobe Illustrator 19.0.0, SVG Export Plug-In . SVG Version: 6.00 Build 0)  -->
<svg version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
	 viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" xml:space="preserve">
<path style="fill:#1976D2;" d="M448,0H64C28.704,0,0,28.704,0,64v384c0,35.296,28.704,64,64,64h384c35.296,0,64-28.704,64-64V64
	C512,28.704,483.296,0,448,0z"/>
<path style="fill:#FAFAFA;" d="M432,256h-80v-64c0-17.664,14.336-16,32-16h32V96h-64l0,0c-53.024,0-96,42.976-96,96v64h-64v80h64
	v176h96V336h48L432,256z"/>
</svg>

```


---
![youtube logo](assets/youtube_logo_30.png) [Insertar imágenes](https://youtu.be/CqpKzS8uLUc)

--- 
![github logo](assets/github_logo_30.png) [Curso HTML 2020/2021](https://github.com/DorianDesings/html-2020-2021)  

---

[Inicio |]() [Anterior |](1contenido_embebido.md) [Siguiente](3device_pixel_ratio.md)

