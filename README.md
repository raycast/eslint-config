# eslint-config-raycast

ESLint configuration for your Raycast extensions. This abstracts away the ESLint TypeScript deps as well as Raycast's ESLint plugin so that you can lint your extensions in a simple way.

## Installation

Next, install `eslint-config-raycast` as part of your dev dependencies:

```sh
npm install eslint-config-raycast --save-dev
```

Note that this package requires `eslint`, `prettier` and `typescript` to be installed.

## Usage

Add `raycast` to the `extends` section of your `.eslintrc` configuration file. You can omit the `eslint-config-` prefix:

```json
{ 
  "extends": [
    "raycast"
  ]
}
```

Note that you can configure the rules you want to use under the rules section:

```json
{
    "rules": {
        "raycast/prefer-title-case": "warn"
    }
}
```