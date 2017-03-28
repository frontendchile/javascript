# JavaScript
Para dominar JavaScript, el lenguaje más versátil y demandado de la actualidad, tienes que conocer sus herramientas, tales como librerías, frameworks, componentes, etc.

## Índice
* [Herramientas](https://github.com/frontendchile/javascript/blob/master/JavaScript.md#herramientas)
   * [Babel](https://github.com/frontendchile/javascript/blob/master/JavaScript.md#babel)
   * [Vue](https://github.com/frontendchile/javascript/blob/master/JavaScript.md#vue)
   * [Gulp](https://github.com/frontendchile/javascript/blob/master/JavaScript.md#gulp)
   * [Grunt](https://github.com/frontendchile/javascript/blob/master/JavaScript.md#grunt)
* [Template](https://github.com/frontendchile/javascript/blob/master/JavaScript.md#template)
* [¿Cómo contribuir?](https://github.com/frontendchile/javascript/blob/master/JavaScript.md#cómo-contribuir)
* [Autor](https://github.com/frontendchile/javascript/blob/master/JavaScript.md#autor)

## HerramientasJS

### Handlebars
* **Categoría:** Sistema de plantillas
* **Descripción:** Handlebars es una extensión de MustacheJS que tiene más prestaciones y mejor rendimiento. Es un sistema de plantillas que permite definir de manera muy sencilla una "plantilla" para datos que vas a mostrar en el navegador para ser más limpio y legible que el común método de concatenar cadenas de carácteres dentro de una matriz mientas recorres un objeto que acabas de recibir o crear del servidor.
* **Competencia:** Mustache
* **Enlaces**
    * **[HandlebarJS.com](http://handlebarsjs.com/ "handlebarsjs.com")**
    * **[Guía de ayuda 1](https://www.funcion13.com/aprendiendo-a-usar-handlebars-como-sistema-de-templates-en-jquery/ "funcion13.com")**
    * **[Guía de ayuda 2](http://blog.hostdime.com.co/que-es-handlebars-js-y-como-usarlo/ "blog.hostdime.com.co")**
    
### Ember
* **Categoría:** Framework UI, SPA
* **Descripción:** Ember.js es un framework JavaScript para crear aplicaciones web del lado del cliente (código abierto). Esta basado en la arquitectura modelo-vista-controlador (MVC). Esta catalogado como unos de los principales framework a en el mundo de JavaScript ya que permite a los desarrolladores crear aplicaciones de una sola pagina (single-page) escalables.
* **Competencia:** Angular, Vue, Polymer, React, Backbone.
* **Enlaces**
    * **[EmberJS.com](https://emberjs.com/ "emberjs.com")**
    * **[Guía de ayuda 1](http://codehero.co/ember-js-desde-cero-introduccion-e-instalacion/ "codehero.co")**
    * **[Guía de ayuda 2](https://www.adictosaltrabajo.com/tutoriales/primera-aplicacion-ember/ "adictosaltrabajo.com")**

### Babel
* **Categoría:** Transcopilador
* **Descripción:** Babel.js es un transcompilador que nos permite convertir nuestro código de JavaScript ES6 en código de ES5. Esta característica se esta convirtiendo en algo crítico para mucha gente ya que las nuevas características de ES6 hacen deseable trabajar con el lenguaje lo antes posible. Lamentablemente hoy en día en la mayor parte de los navegadores y distintas plataformas de JavaScript tienen un soporte parcial de ES6 . Vamos a introducir Babel.js y como nos ayuda a transformar nuestro código de ES6 a ES5.
* **Competencia:** No aplica por el momento.
* **Enlaces**
    * **[BabelJS.io](https://babeljs.io/ "babeljs.io")**
    * **[Guía de ayuda 1](https://abalozz.es/usa-las-nuevas-caracteristicas-de-javascript-hoy-mismo-con-babel/ "abalozz.es")**
    * **[Guía de ayuda 2](http://www.arquitecturajava.com/introduccion-babel-js-javascript-es6/ "arquitecturajava.com")**

### Browserify
* **Categoría:** Dependencias/modulos
* **Descripción:** Browserify es básicamente una herramienta que nos permite gestionar dependencias en forma de módulos del lado del cliente (en el navegador). A grandes rasgos podemos decir que lo que nos permite es crear y requerir módulos tal y como hacemos con Node.js; y digo a grandes rasgos porque no es exactamente así, ya que con browserify no tendremos en el build final varios ficheros javascript, sino que crearemos un bundle con la herramienta y tan solo tendremos un fichero javascript.
* **Competencia:** Webpack.
* **Enlaces**
    * **[Browserify.org](http://browserify.org/ "browserify.org")**
    * **[Guía de ayuda 1](http://www.nazariglez.com/2015/02/19/primeros-pasos-con-browserify/ "nazariglez.com")**
    
### Webpack
* **Categoría:** Dependencias/modulos
* **Descripción:** Webpack es un sistema de bundling para preparar el desarrollo de una aplicación web para producción. En cierta medida se puede considerar un Browserify avanzado ya que tiene muchas opciones de configuración. También se puede considerar una evolución de Grunt y Gulp, ya que permite de alguna manera automatizar los procesos principales que son transpilar y preprocesar código de .scss a .css, de ES7 a ES5/6, etc...
* **Competencia:** Browserify.
* **Enlaces**
    * **[Webpack.JS.org](https://webpack.js.org/ "webpack.js.org")**
    * **[Guía de ayuda 1](https://carlosazaustre.es/blog/primeros-pasos-con-webpack/ "carlosacaustre.es")**

### Vue
* **Categoría:** Framework UI
* **Descripción:** Vue es un framework JavaScript progresivo para la creación de interfaces de usuario. Vue.js añade data binding y reactividad a las aplicaciones web, destaca por ser ligero, flexible, tener una corta curva de aprendizaje y por adoptar lo mejor de los frameworks JavaScript más populares como son AngularJS y React.
* **Competencia:** Angular, React
* **Enlaces**
    * **[VueJS.org](http://vuejs.org/ "vuejs.org")**
    * **[Guía de ayuda 1](https://coligo.io/vuejs-the-basics/ "coligo.io")**
    * **[Guía de ayuda 2](https://laracasts.com/series/learn-vue-2-step-by-step "laracasts.com")**
    * **[Guía de ayuda 3](http://www.beerjs.cl/dic2016/#1 "beerjs.cl")**

### React
* **Categoría:** Librería UI
* **Descripción:** Es una biblioteca Javascript de código abierto para crear interfaces de usuario con el objetivo de animar al desarrollo de aplicaciones en una sola página. Es mantenido por Facebook, Instagram y una comunidad de desarrolladores independientes  y compañías.React intenta ayudar a los desarrolladores a construir aplicaciones que usan datos que cambian todo el tiempo. Su objetivo es ser sencillo, declarativo y fácil de combinar. React sólo maneja la interfaz de usuario en una aplicación; está construida únicamente para utilizar el patrón de diseño modelo–vista–controlador (MVC), y puede ser utilizada conjuntamente con otras bibliotecas de Javascript o más grandes #MVC como AngularJS. También puede ser utilizado con las extensiones de React-based que se encargan de las partes no-UI (no gráficas) de una aplicación web.
* **Competencia:** Angular, Vue
* **Enlaces**
    * **[Facebook.github.io/react](https://facebook.github.io/react/ "facebook.github.io")**
    * **[Guía de ayuda 1](https://carlosazaustre.es/blog/empezando-con-react-js-y-ecmascript-6/ "carlosazaustre.es")**
    * **[Guía de ayuda 2](https://platzi.com/blog/intro-react-js/ "platzi.com")**

### Gulp
* **Categoría:** Librería / Automatizador de tareas
* **Descripción:** Gulp.js es un build system(sistema de construcción) que permite automatizar tareas comunes de desarrollo, tales como la minificación de código JavaScript, recarga del navegador, compresión de imágenes, validación de sintaxis de código y un sin fin de tareas más.
* **Competencia:** Grunt
* **Enlaces**
    * **[GulpJS.com](http://gulpjs.com/ "gulpjs.com")**
    * **[Guía de ayuda 1](https://frontendlabs.io/1669--gulp-js-en-espanol-tutorial-basico-primeros-pasos-y-ejemplos "frontendlabs.io")**
    * **[Guía de ayuda 2](https://platzi.com/blog/automatizacion-gulp-js/ "platzi.com")**
    
### Grunt
* **Categoría:** Librería / Automatizador de tareas
* **Descripción:** Grunt.js es una librería JavaScript que nos permite configurar tareas automáticas y así ahorrarnos tiempo en nuestro desarrollo y despliegue de aplicaciones webs.Con un simple fichero JS que llamaremos Gruntfile, indicamos las tareas que queremos automatizar con un simple comando y las escribimos en él en formato JSON.
* **Competencia:** Gulp
* **Enlaces**
    * **[GruntJS.com](http://gruntjs.com/ "gruntjs.com")**
    * **[Guía de ayuda 1](https://carlosazaustre.es/blog/automatizar-tareas-en-javascript-con-grunt-js/ "carlosazaustre.es")**

## Template

### Componente A
* **Categoría:** Automatizador, framework, librería, componente, paquete, etc.
* **Descripción:** Este es una descripción corta del componente, porque para eso están los enlaces de más abajo, para ver la documentación completa de este. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tristique commodo magna a sagittis. Aliquam tortor libero, molestie quis efficitur nec, venenatis et lectus. Proin pellentesque, leo a interdum imperdiet, ipsum lectus volutpat nunc, at faucibus arcu ipsum ac arcu.
* **Competencia:** Componente B (se pone la compentecia o el "parecido" a otro componente. Ejemplo: Gulp con Grunt)
* **Enlaces**
    * **[Sitio.com](http://sitio.com/ "sitio.com")**
    * **[Guía de ayuda 1](https://frontend.io/ayuda-1 "frontend.io")**
    * **[Guía de ayuda 2](https://ejemplo.io/guia-para-empezar "ejemplo.io")**

## Autor
Comunidad FrontEnd Chile
