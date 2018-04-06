# @madiodio/eslint-config-personal

## Install

```bash
npm install --dev @madiodio/eslint-config-personal
```

## Usage

1.  First run this to find out the correct dependencies listed by this command:

```bash
npm info "@madiodio/eslint-config-personal" peerDependencies
```

...then run `npm install --dev [package]` for all the packages listed.

If using npm 5+ then you're lucky, use this shortcut instead:

```bash
npx install-peerdeps --dev @madiodio/eslint-config-personal
```

...Or you can simply run this:

```bash
npm install --dev @madiodio/eslint-config-personal eslint-config-airbnb eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-flowtype babel-eslint eslint
```

2.  Add this to your .eslintrc file:

```
{
  "extends": "@madiodio/eslint-config-personal"
}
```

Settings are overridable from the shareable config by adding them directly into your
`.eslintrc` file.

## External Configs and Plugins

The following are the configs and plugins from which this package `extends` its rules:

* eslint:recommended
* [eslint-config-airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb)
* [eslint-config-prettier](https://github.com/prettier/eslint-config-prettier)
* [eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import)
* [eslint-plugin-jsx-a11y](https://github.com/evcohen/eslint-plugin-jsx-a11y)
* [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react)
* [eslint-plugin-flowtype](https://github.com/gajus/eslint-plugin-flowtype)

## Disabled Rules

The eslint `rules` which are turned off by this package are listed [here](https://github.com/madiodio/eslint-config-personal/blob/master/rules/es6.js#L35)

## Inspirations

* [eslint-config-smagrassi](https://github.com/StefanoMagrassi/eslint-config-smagrassi)
* [eslint-config-smooth](https://github.com/smooth-code/eslint-config-smooth)

## License

MIT
