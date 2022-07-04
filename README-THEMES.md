## Themes

To vary, for example, the volt themes basic colours create a
file in *src/scss/themes*.

*src/scss/themes/_custom.scss*
```
$primary: #0d6efd;
$secondary: #6c757d;
```

Run the following commands:

    npm install
    npx gulp build:css:themes


The newly build CSS files are in */dist/css/*

```
volt.custom.css
volt.custom.css.map
volt.custom.min.css
volt.css
volt.css.map
volt.min.css
volt.min.min.css
```


