# CrudUi

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Versions that I have used:

UI Versions:
Angular - 16.2.0
Node: 20.5.1
npm: 9.8.0
Bootstrap: 5.3.1
Angular Material: 16.2.2

Backend Versions:
Java: 17.0.8
Maven: 3.9.4
Spring Boot: 3.1.3


## Install bootstrap and material UI in angular project:
<pre>
Bootstrap steps:
1. npm install bootstrap jQuery
2. In angular.json file
   In styles array: 
        "src/styles.css",
        "node_modules/bootstrap/dist/css/bootstrap.min.css"
   In scripts array:
        "node_modules/jquery/dist/jquery.min.js",
        "node_modules/bootstrap/dist/js/bootstrap.min.js"

Material UI steps:
1. ng add @angular/material
2. Choose theme and we are good to go
</pre>
