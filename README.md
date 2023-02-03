# Raycast ESLint Configuration

ESLint configuration for your Raycast extensions. This abstracts away the ESLint TypeScript deps as well as Raycast's ESLint plugin so that you can lint your extensions in a simple way.

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

Note that you can configure the rules you want to use under the rules section:

```json
{
    "rules": {
        "@raycast/prefer-placeholders": "warn"
    }
}
```