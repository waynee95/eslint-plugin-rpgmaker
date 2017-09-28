eslint-plugin-rpgmaker
======================

> [`ESLint`](http://eslint.org) ESlint Plugin for RPG Maker MV Globals.

## Installation

```sh
$ npm install eslint-plugin-rpgmaker --save-dev
```

## Configuration

Add `plugins` section and specify eslint-plugin-rpgmaker as a plugin.

```json
{
  "plugins": [
    "rpgmaker"
  ]
}
```

Add `mv` to the env section.

```json
{
  "env": {
        "rpgmaker/mv": true
    }
}
```
