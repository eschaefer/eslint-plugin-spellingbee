# eslint-plugin-spellingbee

Catches common misspellings that can result result in nasty bugs.

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-spellingbee`:

```
$ npm install eslint-plugin-spellingbee --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-spellingbee` globally.

## Usage

Add `spellingbee` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
  "plugins": ["spellingbee"]
}
```

Then configure the rules you want to use under the rules section.

```json
{
  "rules": {
    "spellingbee/no-misspelled-length": 2
  }
}
```
