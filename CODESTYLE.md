# Codestyle

In this file we define conventions that we use in the project and we have not got
automated checks for them yet.


- file naming: use kebab-case instead of camelCase for file names because changing lower case letters to capital ones have caused problems in every one of my projects.
- file naming: start file names with small letters
- tests are always next to their implementation, in the same directory
- test files are called `<component-name>.test.ts`
- we use a domain driven structure (`user`, `product`), instead of feature driven (e.g.: `views`, `stores`, etc..)
