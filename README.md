# EddieBotMap

![screenshot](https://user-images.githubusercontent.com/624760/89235454-1e8d6a00-d5e6-11ea-9c65-8f518b6be785.png)

---

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.0.

## Quick Start

1. Clone the project
2. Install dependencies by running the command `npm install`
3. Set up environment variables
   * Open `/src/environments/environment.ts` add your firebase config
    ```typescript
    export const environment = {
      production: false,
      firebase: {
         apiKey: '<your-key>',
         authDomain: '<your-project-authdomain>',
         databaseURL: '<your-database-URL>',
         projectId: '<your-project-id>',
         storageBucket: '<your-storage-bucket>',
         messagingSenderId: '<your-messaging-sender-id>'
      }
    };
    ```
  

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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
