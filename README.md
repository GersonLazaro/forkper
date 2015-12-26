# Forkper 2.0.0 Ghost Theme

Demo: [GersonLazaro.com](http://www.GersonLazaro.com)

Tema basado en [Casper](https://github.com/TryGhost/Casper) para [Ghost](http://github.com/tryghost/ghost/).
Para descargar, visita la pagina de [lanzamientos](https://github.com/GersonLazaro/forkper/releases/).


## Instalación

1. Descomprime el tema en la carpeta "content/themes" de tu instalación de Ghost.
2. Abre el archivo index.hbs y edita los links a tus redes sociales.
3. Añade tu codigo de seguimiento de google analytics en default.hbs.
Reemplaza el texto "TU CODIGO DE SEGUIMIENTO" por el codigo de analytics de tu pagina.
IMPORTANTE: No elimines las comillas simples que rodean el codigo. La linea debe quedar asi:
ga('create', 'UA-XXXXXXXX-X', 'auto');
4. Reemplaza el texto "USERNAME" en el archivo post.hbs por el shortname de tu sitio en disqus
IMPORTANTE: No elimines las comillas simples del username
5. Ve al administrador de Ghost, y en "settings/general/themes" selecciona Forkper 

Opcional: Si deseas eliminar un boton de red social puedes hacerlo sin problemas: elimina todo el div que lo contiene

## Caracteristicas

* Compatibilidad con tags mejorados
* Integración de redes sociales en la pagina inicial
* Nueva disposición del footer (central, mas visible).
* Integración inmediata con comentarios Disqus.
* Integración inmediata con google Analytics.
* Compatibilidad con Facebook Open Graph y twitter Cards.
* Tema en español (Algunas palabras no dependen del tema sino de Ghost y no pueden
traducirse desde aqui. Todas las demas, vienen por defecto en español).
* Eliminación del menú lateral de navegación.
* Ajustes en los botones de compartir en redes sociales.
* Compatible con Ghost 0.7.x.


## Como contribuir

Todas las ideas y ayudas son bienvenidas. Si quieres proponer un cambio, o reportar un bug, ve a "issues" y reportalo
(no olvides colocar la etiqueta "feature" o "bug" según corresponda). Los issues en español e ingles son bienvenidos. 
Trata de detallar claramente tu idea.

Si deseas colaborar directamente con los cambios, realiza un fork, informa en un issue el cambio que vas a realizar,
y una vez lo tengas listo, solicita un pull request.


## Contacto

Si lo que quieres es proponer cambios o reportar fallos, ve a la sección anterior. De lo contrario:

Correo: [GersonLazaro@GersonLazaro.com](mailto:GersonLazaro@GersonLazaro.com). 
Twitter: [@GersonLazaroC](http://www.twitter.com/GersonLazaroC)


## Licencia

El contenido de este repositorio se encuentra publicado bajo una [Licencia MIT](LICENSE).

