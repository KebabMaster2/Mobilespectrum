# MobileSpectrum

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.0.1.

## Requirements

* NodeJS 14.15
* Angular CLI
* Yarn

## Build and Deploy to production

### Without Docker

```
ng build --prod
```

And copy static `dist/MobileSpectrum` to webserver root directory. 

### Docker

```
docker-compose build
docker-compose up -d
```

## Development

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.