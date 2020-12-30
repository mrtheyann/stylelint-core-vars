# stylelint-core-vars

[![NPM Version](https://img.shields.io/npm/v/stylelint-core-vars.svg)](https://www.npmjs.com/package/stylelint-core-vars)

[Stylelint](http://stylelint.io) плагин, проверяющий использование [дизайн-токенов](https://github.com/alfa-laboratory/core-components/tree/master/packages/vars/src)

## Установка

```
yarn add --dev stylelint stylelint-core-vars
```
или
```
npm install --save-dev stylelint stylelint-core-vars
```

## Использование

Добавьте в свой stylelint конфиг:

```
{
  "plugins": [
    "stylelint-core-vars"
  ],
  "rules": {
    "stylelint-core-vars/use-vars": true
  }
}
```