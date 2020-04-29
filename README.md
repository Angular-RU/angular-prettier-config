# Shareable Prettier config for Angular projects

<p>
  <a href="https://travis-ci.org/angular-ru/angular-prettier-config">
    <img src="https://travis-ci.org/Angular-RU/angular-prettier-config.svg?branch=master" />
  </a>
  <a href="https://badge.fury.io/js/%40angular-ru%2Fprettier-config">
    <img src="https://badge.fury.io/js/%40angular-ru%2Fprettier-config.svg" />
  </a>
  <a href="https://npm-stat.com/charts.html?package=%40angular-ru%2Fprettier-config&from=2019-09-01">
    <img src="https://img.shields.io/npm/dw/@angular-ru/prettier-config" />
  </a>
</p>

### Quick start

```bash
$ npm install @angular-ru/prettier-config -D
```

Add to your `package.json`:

```json
{
    "name": "my-app-project",
    "version": "9000.0.1",
    "prettier": "@angular-ru/prettier-config"
}
```

or `.prettierrc.js`:

```js
module.exports = {
    ...require('@angular-ru/prettier-config'),
    semi: false
};
```
