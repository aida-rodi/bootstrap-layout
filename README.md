# S2.Maquetació II

## Abans de començar el projecte
1. Instalar Nodejs (descarregar de nodejs.org) ✔

2. Instalar package.json (desde terminal) ✔
npm init

3. Instalar Bootstrap (desde terminal) ✔
npm install bootstrap

4. Crear archivo SASS (en una carpeta nueva llamada **sass**) ✔
main.scss --> ( luego lo convertimos en archivo css)

5. Anar a extension settings del Live Sass Compiler i modificar el settings.json de la categoria format per que guardi el css a la carpeta /css en format comprimit .min.css ✔

*HTML lo que entiende es css, hay que hacer el link del html al css (no al scss). Una vez que consigo instalar #PurgeCss de abajo y realizar todos los cambios pertinentes, entonces volver a cambiar el link de main.css a REDUCIDO.CSS*

## En acabar el projecte
1. Instalar PurgeCss (desde terminal)
  npm i -g purgecss

<!--  ir a package.json encontrar "scripts": {} ES PARA OPTIMIZAR el codigo CSS, para que guarde solo lo que uso en mi codigo y asi tendria que crearse una carpeta nueva de REDUCIDO.CSS ... FALTA ESTA PARTE DE ACABARLA, VER VIDEO tiempo 1.17hora-->
npm run build

### CUANDO TERMINO MI PROYECTO, HAY QUE VOLVER A TERMINAL Y REINICIAR LOS CAMBIOS CON:
  npm run build

### Si quiero subir mi proyecto a una pagina de hosting (por ej: netlyfy.com) entonces debo crear en local una carpeta 'dist' y allí guardar:
  - html
  - reducido.css
  - images

Desde esta pagina me dan un dominio y si lo quiero personalizar, tengo que dar a SETTING -> Options -> Edit Site name (escribo nombre de mi poyecto) -> Save