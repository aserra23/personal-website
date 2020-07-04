# PersonalWebsite

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.6.

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

## GAE Creation

- Buy Domain
- Register Domain in Google Cloud Platform (GCP)
- Create Project name in GCP
- Create Google App Engine (GAE)
- Create git repo (Github)
- `git clone` to your OS in Desktop or GAE
- create angular app using `ng new <application name>`and place it in git directory
- create a `app.yaml` file in angular app and place it in `dist/` folder `<application name>/dist/app.yaml`
- make sure spacing is correct in yaml file and that proper `runtime` is given
- do `git pull` in GAE 
- perform `ng build` in GAE and fix any npm/node issues that arise
- do `gcloud app create` in GAE pick a region and project id. This will be done one per project
- do `gcloud app deploy` in GAE and fix any yaml issues that arise

