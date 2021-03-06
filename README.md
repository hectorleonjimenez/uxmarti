![Logo Marti](http://201.163.233.36:7003/store-marti/menu_mobile/assets/images/logos/marti.png)

# Comentarios

Sencilla estructura para proyecto web de marti.mx.

## Características:

* Usa gulp para automatizar tareas
* Esta basado en Sass, Pug y ES6.
* Compila Sass con autoprefixer y muestra los cambios en tiempo real
* Compila Pug y actualiza el navegador con cada cambio
* Compila ES6 con soporte para módulos ES6 (importar y exportar modulos)
* Detecta nuevos archivos añadidos al proyecto sin tener que reiniciar gulp
* Captura errores en Sass, Pug y Js evitando que gulp se detenga.
* Crea los sourcemaps de los archivos compilados
* Tiene una estructura lista de estilos (con Sass) basada en SMACSS y ITCSS
* Tiene una estructura lista para HTML (con Pug) que divide páginas e includes.
* Tiene una estructura lista para importar y exportar modulos ES6

## Modo de uso

1. Descargue Node y NPM  de https://www.npmjs.com/get-npm
2. Ejecute node -v en su terminal, para comprobar que node se instalo correctamente.
3. Ejecute npm -v en su terminal, para comprobar que nPM se instalo correctamente.
4. Clone este repositorio.
5. Ejecute `npm install` en el directorio raiz.
6. Ejecute `gulp` en el directorio raiz.

## Estructura

1. La carpeta dev contiene la estructura de archivos con la que trabajará
2. La carpeta public contiene los archivos compilados que deberan llevarse a producción
3. Para Sass importe sus partials desde `styles.scss`, el orden está indicado en el mismo archivo
4. Para Pug, la carpeta `pages` contiene las paginas del proyecto y la carpeta `includes` los bloques.
5. Para Js, la carpeta `modules` contiene los módulos que serán importados desde `index.js`