# AlgoTrading

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.1.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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

ng update @angular/core@14

Angular deployment
-----------
npm i angular-cli-ghpages --save-dev
ng build --base-href "https://ashishkvs.github.io/algo-trading-view/"
 Make sure you put in your Github username in “GithubUserName” and the repository name you created in “GithubRepoName” sections of the URL.

 --deploy
 ========
 npx angular-cli-ghpages --dir=dist/algo-trading-view

 CHROME-enable isecure content
 ------------------------------
 chrome://settings/content/insecureContent?search=insecure