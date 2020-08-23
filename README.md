# CoImage

This is demo Image uploader and retriever project

## Installation

- Run `bash setup/setup.sh` for installation and aws bucket creation (please make sure creds present in ./aws_credentials has access to AmazonS3FullAccess ).
- Create RDS instance and update credentials [here](/server/config/dev.js) or install mysql locally

## Development server

Run `npn run all` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running tests

Run `npm run devtest` to execute the tests with coverage.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
