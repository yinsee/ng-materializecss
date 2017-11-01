# GmMaterializecss

Created following this post

https://medium.com/@ladyleet/using-materializecss-with-your-angular-2-angular-cli-app-2eb64b05a1d2

### 1. Setting up library
```
npm install --save materialize-css jquery
```

### 2. Setting up .angular-cli.json
```
  "styles": [
    "styles.css",
    "../node_modules/materialize-css/dist/css/materialize.css"
  ],
  "scripts": [
    "../node_modules/jquery/dist/jquery.min.js",
    "../node_modules/materialize-css/dist/js/materialize.js"
  ],
```




To be improved... (global jQuery with webpack plugin?)