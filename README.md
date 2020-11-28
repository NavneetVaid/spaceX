# Spacex

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.0.2.

## Running on local
After cloning you would need to run npm install on local to download all the dependencies.

## Architecture
This project uses server side rendering with the help of ng universal. All components are loaded in one root module app module. There is a service folder which consist a injectable service which holds the call to the spacex api. The application has 3 components 
- App component
- Cards component 
- Filters component 

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests. The angular.json and package.json has been updated to show the test coverage as well with this command.

## Deployment

The code has been deployed to Heroku (https://spacex-publicis.herokuapp.com/). There is a pipeline created to automatically deploy the changes if there is any push in the main branch.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
