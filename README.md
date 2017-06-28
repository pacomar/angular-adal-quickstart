# ng2-adal Quickstart

The very well known updated Angular Quickstart repository updated with ng2-adal, a module based on angular2-adal, a very well written library that is known to cause some problems because of rapid breaking changes in Angular.

This one works and I am currently using this for a personal project.

Please let me know in case of bugs/issues.

## How to Use

1. Rename app/services/secret.service.ts.template to app/services/secret.service.ts and add your  tenant and client ID.
2. Remove secret.service.ts from .gitignore
3. Run `npm install`
4. Run `npm start`

## Getting Token as a String

Use `services/auth.service.ts`. This token needs to be passed as a header for REST service authentication.