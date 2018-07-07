# Juiceboxes/juice-grid

Boilerplate for web development with Pug and Sass. 

Built using npm scripts.

No gulp, no grunt, no webpack.

## Structure

```
yourProject
├───dist
│   ├─── base.css (compiled)
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
Builds `index.pug` and `base.scss` for TravisCI > `npm run test`

Builds `index.pug` and `base.scss`, watches for changes > `npm run start`

Builds `index.pug` and `base.scss` > `npm run build`

Builds `index.pug` > `npm run build:pug`

Builds `base.scss` > `npm run build:sass`

Watches `index.pug` and `base.scss` for changes > `npm run watch`

Watches `index.pug` for changes > `npm run watch:pug`

Watches `base.scss` for changes > `npm run watch:sass`