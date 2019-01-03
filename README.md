# ESLint Config Ladybug
My personal eslint config file that is used in all of my projects

## Install
You can still use it if you want
```sh
npm install -g pollen5/eslint-config-ladybug
```
> **Note:** Remove `-g` if you are using a local eslint install, in the command above we assumed you installed eslint globally

### Yarn
With yarn you can use
```sh
yarn global add pollen5/eslint-config-ladybug
```
> Again remove `global` if using a locally installed eslint.

## Usage
Create a `.eslintrc.json` in your project
```json
{
  "extends": "ladybug"
}
```
You are all set, feel free to add the `"rules"` section and override some if you don't like it

## React
For react config use
```json
{
  "extends": "ladybug/react"
}
```
You will need this two modules
```sh
npm install -g babel-eslint eslint-plugin-react
# or yarn
yarn global add babel-eslint eslint-plugin-react
```
> Repeating once again: remove `-g|global` if using a locally installed eslint

## TypeScript
A TSLint config is also available to use, to use this you just need `tslint` installed.
```json
{
  "extends": ["eslint-config-ladybug/typescript"]
}
```
The TSLint preset also extends `tslint:recommended` so you don't need that.

## Contributing
You could change some rule and submit it as a Pull Request but the chances are gonna be low depends if i like that style.

## License
[MIT](LICENSE)
