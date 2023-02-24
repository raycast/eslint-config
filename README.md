# Raycast ESLint Config


Raycast provides an opinionated configuration by default that includes everything you need to lint your Raycast extensions. 

## Installation

Install `@raycast/eslint-config` as part of your dev dependencies:

```sh
npm install @raycast/eslint-config --save-dev
```

Note that this package requires `eslint`, `prettier` and `typescript` to be installed.

## Usage

Add `@raycast` to the `extends` section of your `.eslintrc` configuration file.

```json
{ 
  "extends": [
    "@raycast"
  ]
}
```

## Configuration

Configure the rules you want to use under the `rules` section:

```json
{
  "extends": [
    "@raycast"
  ],
  "rules": {
    "@raycast/prefer-placeholders": "warn"
  }
}
```
