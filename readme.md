# Ryu Technology

Este site es de una empresa dedicada al rubro tecnológico de la ingeniería de redes y su aplicación en el ámbito de comunicaciones, seguridad, automatización y domótica,
tanto a nivel empresarial como en los hogares.

## Comenzando 🚀

Este es un proyecto público, puedes decargarte una copia desde la pestaña code 😊

Mira **Deployment** para conocer como luce el proyecto.

El proyecto está formado por 5 páginas:  index, proyectos, partners, empresa y contacto.

El archivo principal de SASS es styles.scss, desde éste se llaman mediante partials a las otras
hojas:

    > _headers contiene los encabezados de todas las páginas.
    > _footers contiene los footers utilizados en las páginas.
    > _iniciales contiene los parámetros iniciales del proyecto.
    > _secciones contiene todo el contenido de todas las páginas.
    > _mediaquery contiene todos los cambios en los diferentes breakpoints (responsive).
    > _mixin contiene los códigos comunes para ahorrar líneas en el CSS.
    > _variables contiene algunas variables para futuros cambios de estilo.

El SASS compila del archivos style.scss de la carpeta SCSS, en el archivo stylesscss.css en la
carpeta CSS (ver archivo package.json)

### Pre-requisitos 📋

Para poder usar los SCSS, es necesario tener instalado node.js y tener instalado nodemon.
Puedes utilizar Visual Studio Code o Sublime Text para revisarlo 🔧

### Instalación 

Estas instrucciones están hechas para Visual Studio Code, con el cual lo realicé:

* Instala **node.js** y **npm** desde https://nodejs.org/es/download/

* En el Visual Studio Code úbicate en el directorio del proyecto

* Inicia el npm, con npm init en TERMINAL (Ctrl + ñ)

* Instala el nodemon con: **npm install -D node-sass nodemon**

* Compila con npm: **run watch-css**

Si ya tienes instalado el node.js, ya están incluidos los files package.json y los .scss, puedes editar directamente los .scss 😊
y solamente compilar el proyecto para comenzar.


## Construido con 🛠️


* La mayor parte del código está hecho directamente con CSS en Visual Studio Code 1.62.2

* Se uso bootstrap 5.1 para algunas secciones (header, footers)

* La fuente del texto fueron tomadas de Google Fonts

* Algunas animaciones fueron tomadas de https://animate.style/


## Autor✒️

Este proyecto fue realizado para las clases de Desarrollo Web de CoderHouse por:

**Ing. Luiggi Márquez** - (https://github.com/luiggimarquez) ✌️

Buenos Aires, Argentina 2022


