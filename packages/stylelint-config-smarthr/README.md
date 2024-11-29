# stylelint-config-smarthr

[![npm version](https://badge.fury.io/js/stylelint-config-smarthr.svg)](https://badge.fury.io/js/stylelint-config-smarthr)

A sharable stylelint config for SmartHR.
This is intended to use for a project with styled-components.

## Install

```sh
pnpm add --dev stylelint stylelint-config-standard stylelint-config-styled-components postcss-styled-syntax // install peerDependencies
pnpm add --dev stylelint-config-smarthr
```

## How to use

Add a following `.stylelintrc` in your project.

```json
{
  "extends": [
    "stylelint-config-smarthr"
  ]
}
```