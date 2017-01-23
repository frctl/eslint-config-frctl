# eslint-config-frctl

ESLint configuration to be shared across all Fractal repositories.

[![NPM Version](https://img.shields.io/npm/v/@frctl/eslint-config-frctl.svg?style=flat-square)](https://www.npmjs.com/package/@frctl/eslint-config-frctl)

## Overview

This package is an [ESLint shareable config](http://eslint.org/docs/developer-guide/shareable-configs) which can be used in conjunction with an ESLint based plugin such as [xo](https://github.com/sindresorhus/xo), in order to help maintain consistent styles across a codebase.

```
"xo": {
  "extends": "@frctl/eslint-config-frctl"
}
```

## Installation

Installation is via [npm](https://www.npmjs.com/).

`npm i @frctl/eslint-config-frctl`


## Usage
To use with `xo`, first ensure the package has been installed (see above) and then pass the package name to the the [`extends`](https://github.com/sindresorhus/xo#extends) option in `package.json`:

```
{
  "name": "repo-name",
  ...
  },
  "devDependencies": {
    "@frctl/eslint-config-frctl": "0.1.0"
  },
  "xo": {
    "extends": "@frctl/eslint-config-frctl"
  }
}
```

## Requirements
Node: >= 6.0.0
