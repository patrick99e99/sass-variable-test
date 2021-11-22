Demonstration showing global variables in sass not working.

Simply run:

`./node_modules/.bin/webpack --config config/webpack/development.js`

and you will see:

```
ERROR in ./app/javascript/stylesheets/base.scss
Module build failed (from ./node_modules/sass-loader/dist/cjs.js):
SassError: Undefined variable.
  ╷
2 │   color: $color;
  │          ^^^^^^
  ╵
  app/javascript/stylesheets/base.scss 2:10  root stylesheet
SassError: SassError: Undefined variable.
  ╷
2 │   color: $color;
  │          ^^^^^^
```
