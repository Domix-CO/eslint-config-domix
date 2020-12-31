# eslint-config-domix

Core coding standards for @Domix-CO projects.

## Installation

You'll need to install [`ESLint`](https://www.npmjs.com/package/eslint) and [`Prettier`](https://www.npmjs.com/package/prettier) into your project. Use this shortcut to install them alongside the config (if using **npm 5+**):

```sh
npx install-peerdeps --dev eslint-config-domix
```

If you already have `eslint` and `prettier` installed in your project, just run this command to install the config:

```sh
npm install --save eslint-config-domix
```

## Usage

Create a `.eslintrc` file with the following contents:

```js
{
  "extends": [
    "domix"
  ]
}
```

## Configs
> **Note:** `domix/*` subconfigs must be loaded alongside `domix`, or at least take advantage of a root `.eslintrc` config that has `root` set to `true`.

* `domix`
* `domix/react`
* `domix/typescript`


## Contributing
To assist in cleaner commit logs and a better changelog, all commit messages must be formatted against the https://commitlint.js.org/ standards.

See [@commitlint/config-conventional](https://www.npmjs.com/package/@commitlint/config-conventional) for some more information.
