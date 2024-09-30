# Full-Stack-Angular-MPaucar

Angular Full Stack es un proyecto para empezar fácilmente con la última versión de Angular utilizando un backend y una base de datos reales. Toda la pila está en TypeScript, desde el frontend hasta el backend, lo que te brinda la ventaja de codificar en un solo lenguaje en toda la pila.

Este proyecto utiliza la [pila MEAN](https://es.wikipedia.org/wiki/MEAN_(paquete_de_software)):
* [Mongoose.js](http://www.mongoosejs.com) ([MongoDB](https://www.mongodb.com)): base de datos
* [Express.js](http://expressjs.com): framework de backend
* [Angular 2+](https://angular.io): framework de frontend
* [Node.js](https://nodejs.org): entorno de ejecución

Otras herramientas y tecnologías utilizadas:
* [Angular CLI](https://cli.angular.io): estructura de frontend
* [Bootstrap](http://www.getbootstrap.com): diseño y estilos
* [Font Awesome](http://fontawesome.com): íconos
* [JSON Web Token](https://jwt.io): autenticación de usuarios
* [Angular 2 JWT](https://github.com/auth0/angular2-jwt): ayudante JWT para Angular 2+
* [Bcrypt.js](https://github.com/dcodeIO/bcrypt.js): encriptación de contraseñas

## Requisitos previos
1. Instalar [Node.js](https://nodejs.org) y [MongoDB](https://www.mongodb.com)
2. Instalar Angular CLI: `npm i -g @angular/cli`
3. Desde la carpeta raíz del proyecto, instala todas las dependencias: `npm i`

## Ejecución
### Modo de desarrollo con seguimiento de archivos
`npm run dev`: [concurrently](https://github.com/kimmobrunfeldt/concurrently) ejecuta MongoDB, compilación de Angular, compilador de TypeScript y servidor Express.

Se abrirá automáticamente una ventana en [localhost:4200](http://localhost:4200). Los archivos de Angular y Express están siendo monitoreados. Cualquier cambio crea automáticamente un nuevo paquete, reinicia el servidor Express y recarga tu navegador.

### Modo de producción
`npm run prod`: ejecuta el proyecto con un paquete de producción escuchando en [localhost:3000](http://localhost:3000)

### Modo manual
1. Compila el frontend: `npm run build:dev` para dev o `npm run build` para prod
2. Compila el backend: `npm run predev`
3. Ejecuta MongoDB: `mongod`
4. Ejecuta la aplicación: `npm start`

### Docker
1. `sudo docker-compose up`
2. Ve a [localhost:3000](http://localhost:3000)

## Vista previa
![Vista previa](https://raw.githubusercontent.com/miltonAlan/Full-Stack-Angular-MPaucar/master/demo1.png "Vista previa 1")
![Vista previa](https://raw.githubusercontent.com/miltonAlan/Full-Stack-Angular-MPaucar/master/demo2.png "Vista previa 2")
![Vista previa](https://raw.githubusercontent.com/miltonAlan/Full-Stack-Angular-MPaucar/master/demo3.png "Vista previa 3")

## Por favor, abre un problema si
* tienes alguna sugerencia para mejorar este proyecto
* has notado algún problema o error

## Ejecución de pruebas
Ejecuta `ng test` para ejecutar las pruebas unitarias del frontend a través de [Karma](https://karma-runner.github.io).

Ejecuta `npm run test:be` para ejecutar las pruebas del backend a través de [Jest](https://jestjs.io/) (requiere que `mongod` esté en ejecución).

## Ejecución de linters
Ejecuta `npm run lint` para ejecutar [Angular ESLint](https://github.com/angular-eslint/angular-eslint), [linting de HTML](https://github.com/htmlhint/HTMLHint) y [linting de SASS](https://github.com/sasstools/sass-lint).

## Ayuda
Si necesitas asistencia o tienes preguntas sobre el proyecto, no dudes en contactarme a través de mi correo electrónico: [miltonpaucar99@gmail.com](mailto:miltonpaucar99@gmail.com).
