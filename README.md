# prettier-config
My personal configuration for [Prettier](https://prettier.io/). It makes the following adjustments to Prettier's default configuration:

- I do not like semicolons everywhere, hence it sets `semi: false` and
- I prefer single over double quotes, hence it sets `singleQuote: true`.



## Install and use
1. Install this package using npm
```
npm i --save-dev @henningkerstan/prettier-config
```

2. Modify `package.json` and add line
```
"prettier": "@henningkerstan/prettier-config"
```

