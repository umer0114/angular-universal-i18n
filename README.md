# Angular Universal with integrated i18n

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.5. It has angular universal and i18n integrated simultaneously.

For the development of this project, I have created two separate builds; One for client side, while the other for server side. For localization a separate build for each language is made so as to support localization for both server/client side. 

Here is the demo video: https://umer0114.tinytake.com/tt/NDI4MzM2OF8xMzQ1MDIwNw

For server side builds, following are the build commands:
    "serve:ssr-en": "set LANGUAGE=en && node dist/demo-project/server/en/main.js",
    "serve:ssr-pl": "set LANGUAGE=pl && node dist/demo-project/server/pl/main.js",
    "build:ssr": "ng build --prod --localize && ng run demo-project:server:allLocales",
    
Currently, this project supports English 'en' and Polish 'pl' languages. 
