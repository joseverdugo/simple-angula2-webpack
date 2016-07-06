# Angular 2 + WebPack con TypeScript

[![Dependency Status](https://david-dm.org/joseverdugo/simple-angula2-webpack.svg)](https://david-dm.org/joseverdugo/simple-angula2-webpack)

Basado en documentacion oficial de angular 2 con webpack, pero sin Karma ni Jasmine.
https://angular.io/docs/ts/latest/guide/webpack.html 

###Iniciar.

npm install
npm start (port:8080)
npm run build

###Descripcion de Archivos:
- package.json : Definición nom de dependencias para modo desarrollo y producción.
- webpack.config.js : Configuracion de webpack.
- typings.json : Administrador de dependencias TypeScript. Ej: jQuery en typeScript
- tsconfig.json : Configuración del compilador TypeScript 
- config/webpack.prod.js : Configuracion webpack para compilar el proyecto. Se ejecuta con "npm run build" y el el compilado queda en directorio "dist"
- config/webpack.dev.js : Configuracion webpack para ejecutar en modo desarrollo. Se ejecuta con "npm start".
- config/webpack.common.js : Configuracion comun de webpack. 
- config/helpers.js : Configuracion comun de webpack. 
- src/vendor.ts 
- src/main.ts
- src/index.html
- src/polyfills.ts
- src/app/app.component.spect.ts
- src/app/app.component.ts
- src/app/app.component.html
- src/app/app.component.css
- src/css/styles.css
- src/images/angular.png

