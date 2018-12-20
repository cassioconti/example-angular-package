# Ratify

This Angular app contains an Angular library inside projects/ratify.

Build library with `npm run build ratify`.
From the folder `dist/ratify` you can either:
- `npm link` and then `npm link ratify` on the project you want to import.
- `npm pack` to generate a tarball to be installed.
- `npm publish` to push your package to the npm registry.

To increment a version, cd to the folder `project/ratify` and run `npm version patch|minor|major`.

Use the library by importing the module to your AppModule:
```
import { RatifyModule } from 'ratify';

@NgModule({
    ...
  imports: [
    ...
    RatifyModule
  ],
  ...
})
```

And use the RatifyComponent in your HTML:
```
<cc-ratify></cc-ratify>
```

# CcAngularPackage

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.1.4.

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