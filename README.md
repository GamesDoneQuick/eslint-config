# GDQ's eslint-config [![npm](https://img.shields.io/npm/v/@gamesdonequick/eslint-config.svg)](https://www.npmjs.com/package/@gamesdonequick/eslint-config) [![Build Status](https://dev.azure.com/gamesdonequick/eslint-config/_apis/build/status/GamesDoneQuick.eslint-config?branchName=master)](https://dev.azure.com/gamesdonequick/eslint-config/_build/latest?definitionId=6&branchName=master)

> Our re-usable config for the ESLint JS/TS linter.

## Usage

1. Install this config as a devDependency:

   ```bash
   npm i -D @gamesdonequick/eslint-config
   ```

2. Follow the instructions here to use or extend our config: https://eslint.org/docs/developer-guide/shareable-configs#using-a-shareable-config

3. This package actually includes multiple configs. One base config, one that adds typescript support, and one that adds react support. You can pick and choose what parts you wish to use. To use all three, your config might look like this:

   ```js
   module.exports = {
      extends: [
         "@gamesdonequick/eslint-config/react",
         "@gamesdonequick/eslint-config",
         "@gamesdonequick/eslint-config/typescript"
      ]
   };
   ```
