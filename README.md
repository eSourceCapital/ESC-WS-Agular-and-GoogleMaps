# Google Maps with Angular

## Estrucura
La carpeta 01.my-first-map, contiene la base para el workshop.

La carpeta 02.my-first-map, contiene el mapa terminado del workshop.

Para ambos casos es necesario cambiar la API key de Google Maps.

## API KEY

Recordar cambiar la API Key en: 
`<script src="https://maps.googleapis.com/maps/api/js?key=[CAMBIAR API KEY]&callback=initMap"></script>`

Por la generada en la consola de [Google](https://console.cloud.google.com/).

[Leer las mejores practicas para el uso de las API Keys](https://cloud.google.com/docs/authentication/api-keys)


## Angular CLI
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.1.0.

## Creación de un nuevo proyecto

Mediante la interfaz de línea de comandos, ejecutar el comando `ng new [nombre del proyecto]` para crear un nuevo proyecto. Movernos a la ruta generada y ejecutar el comando `ng serve` para levantar el servidor de desarrollo. Navegar a `http://localhost:4200/`. La aplicación se recargará automáticamente si se realizan cambios en el código fuente.
`
ng new my-first-map
cd my-first-map
ng serve
`
## Crear un componente
Para crear un componente en Angular se utiliza el comando `ng generate component [nombre del componente]` o `ng g c [nombre del componente]`. También se puede utilizar el comando `ng g c [nombre del componente] --skip-tests` para no generar los archivos de pruebas.

El comando utilizado fue: `ng generete component maps`

## Instalar Angular Google Maps
Para instalar Angular Google Maps, ejecutar el comando `npm install @angular/google-maps` en la carpeta del proyecto.

Para utilizarlo importar el Modulo GoogleMapsModule 
`import { GoogleMapsModule } from '@angular/google-maps'`


## Links importantes

- Google Maps Platform: https://mapsplatform.google.com/
- Google Maps API: https://developers.google.com/maps/documentation/javascript/
- NPM @angular/google-maps: https://www.npmjs.com/package/@angular/google-maps
