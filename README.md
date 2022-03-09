# Client

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

Run `dotnet watch run` for dev .Ndet server

To run Postgres database locally, use Docker (if you have locally running postgres change port e.g 5433:5432)
`docker run --name dev -e POSTGRES_USER=appuser -e POSTGRES_PASSWORD=Passw0rd -p 5432:5432 -d postgres:latest`

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).