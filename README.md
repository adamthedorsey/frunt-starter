# Frunt
A simple, flexible, framework agnostic, front-end build framework.

## Installation

```shell
npm install
```

Uncomment your preferred framework in `style.scss` located at `/src/sass/style.scss`. 

### Example:

```sass
@import "style.bulma"
// @import "style.bootstrap"
// @import "style.default"
```

## Build

```shell
npm run dev
```

or

```shell
npm run watch
```

Frunt uses [Laravel Mix](https://laravel-mix.com/docs/5.0/basic-example) as a Webpack wrapper. It's super easy to configure and has a ton of options.

## Copyright and license

Code copyright 2020 Adam Dorsey. Code released under [the MIT license](https://github.com/adamthedorsey/frunt/blob/master/LICENSE).
