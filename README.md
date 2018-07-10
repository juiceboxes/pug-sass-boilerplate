# Juiceboxes/pug-sass-boilerplate

Boilerplate for web development with Pug and Sass

Built using npm scripts

No gulp, no grunt, no webpack

Includes a `.travis.yml` for Travis CI

## Structure

```bash
yourProject
├───dist
│   ├─── base.css (compiled)
│   ├─── base.min.css (minified css)
│   └─── index.html (compiled)
└───src
    ├─── pug
    │   └─── index.pug
    └─── sass
        ├─── base.scss (imports)
        ├─── partials
        │   └─── _foo.scss
        ├─── utils
        │   └─── _foo.scss
        └─── vars
            └─── _foo.scss
```

## Development Scripts

`npm run test`: Builds `index.pug` and `base.scss` for TravisCI

`npm run start`: Builds `index.pug` and `base.scss`, watches for changes

`npm run build`: Builds `index.pug` and `base.scss`

`npm run build:pug`: Builds `index.pug`

`npm run build:sass`: Builds `base.scss`

`npm run build:ugly`: Builds `base.min.scss`

`npm run watch`: Watches `index.pug` and `base.scss` for changes

`npm run watch:pug`: Watches `index.pug` for changes

`npm run watch:sass`: Watches `base.scss` for changes