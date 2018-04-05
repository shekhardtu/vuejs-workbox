# Vuejs Workbox

## A vuejs development environment setup to code with popular and useful vuejs extensions

### Brief of included extensions

* [vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur) -
  Vue tooling for VS Code, powered by vue-language-server.
* [vue-peek](https://marketplace.visualstudio.com/items?itemName=dariofuzinato.vue-peek) -
  This extension extends Vue code editing with Go To Definition and Peek Definition support for components and filenames in single-file components with a .vue extension. It allows quickly jumping to or peeking into files that are referenced as components (from template), or as module imports

* [auto-rename-tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) -
  Automatically rename paired HTML/XML tag, same as Visual Studio IDE does.

* [auto-close-tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) -
  Automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text does.

* [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script) -
  This extension supports running npm scripts defined in the package.json file and validating the installed modules against the dependencies defined in the package.jso

* [NPM IntelliSense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) -
  Visual Studio Code plugin that autocompletes npm modules in import statements

* [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) -
  VS Code package to format your JavaScript / TypeScript / CSS using Prettier.

* [Sorting HTML and Jade attributes](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-attrs-sorter) -
  Sorting of the tag attributes in the specified order.
* [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer) -
  This extension allows matching brackets to be identified with colours. The user can define which characters to match, and which colours to use.
* [Import Cost VSCode](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) - This extension will display inline in the editor the size of the imported package. The extension utilizes webpack with babili-webpack-plugin in order to detect the imported size.

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integrates [ESLint](http://eslint.org/) into VS Code. If you are new to ESLint check the [documentation](http://eslint.org/).

## Paste these settings in VS code workspace settings

```
{
  "eslint.enable": true,
  "window.zoomLevel": 1,
  "files.trimTrailingWhitespace": true,
  "prettier.singleQuote": true,
  "prettier.trailingComma": "es5",
  "prettier.eslintIntegration": true,
  "prettier.disableLanguages": [],
  "eslint.autoFixOnSave": true,
  "editor.insertSpaces": true,
  "editor.formatOnSave": true, // only if you want auto      //fomattting on saving the file
  "editor.detectIndentation": true,
  "editor.tabSize": 2,
  "editor.formatOnPaste": false,
  "editor.formatOnType": true,
  "editor.renderControlCharacters": true,
  "editor.renderWhitespace": "all",
  "files.exclude": {
    "**/node_modules": true
  },
  "eslint.validate": [
    {
      "autoFix": true,
      "language": "javascript"
    },
    {
      "autoFix": true,
      "language": "vue"
    }
  ]
}
```

## Credits

* Vuejs workbox has created with the help of above mention plugins. Thanks go to the original authors and contributors of the above mentioned plugin.

**Enjoy!**

> Feel free to send pull requests with updates.

```

```
