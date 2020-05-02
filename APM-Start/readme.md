# APM

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.2.1.

### Setting up routing requires the below

- setting up the base path.
- import angular routing module.
- create necessary component that take part in routing.(smart components mostly).
- create route table to configure routes.
- activate those routes either through html or component using routing directives in html / routing service in component.

### setting base path

- for normal development we can set basePath in index.html as <base href="/">

- when we normally deploy in production we need to set basePath to a website folder like
    <base href="/APM/">
  this we can do it manually or  through angular-cli command like.
   ng build --base-href /APM/
