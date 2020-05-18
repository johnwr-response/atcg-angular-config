# Init
```
ng new angular-config
```

# Make sure your have the latest version of the cli
```
npm install -g @angular/cli@latest
```

# Config files

###### .editorconfig
Sets up defauls for those editors supporting this. Visual Studio Code, IntelliJ etc.

###### browserslist
Angular uses this file to define which browsers to compile code for. Less supported browsers equals smaller files (I.e.: IE9-11).

###### angular.json
Application and environment configurations

###### package.json
npm install uses this file to when installing dependencies and versions of them. It contains the minimal compatible versions.

###### package.lock.json
npm install creates this when run. It contains the EXCACT VERSIONS of the dependencies when executed.

###### tsconfig.json
Configures the Typescript compiler

###### tsconfig.app.json
Extends the main tsconfig options for specific runtime compilation

###### tsconfig.spec.json
Extends the main tsconfig options for specific testing compilation

###### tslint.json
Define config for lint

# Example using ng add
#### Installing Angular Material
https://material.angular.io/
```
ng add @angular/material
```

# Using Custom Schematics with ng generate
Example using @angular/material:
```
ng generate @angular/material:nav main-nav
```

# ng update
Analyzes the project and finds packages needed to be updated. Then it prints a table of commands to be run to actually update
```
ng update
```

# Git
```
git remote add origin https://github.com/johnwr-response/atcg-angular-config.git
git push -u origin master
```
