# Angular Essentials - Extension Pack for VS Code
This extension pack for Visual Studio Code adds extensions that are amazingly useful for Angular development.

See the [CHANGELOG](CHANGELOG.md) for the latest changes

I am often asked, "What are you favorite VS Code extensions for Angular?". I decided it was time to share them via an extension pack.

Introducing my [Angular Essentials extension pack for VS Code](https://marketplace.visualstudio.com/items?itemName=johnpapa.angular-essentials). By installing this extension pack you get a set of great extensions that are helpful with Angular development. You can check out the initial list below.

> As web tools evolve, the usefulness of extensions come and go. I reserve the right to update the extension pack's contents up to my own discretion.

## Recommended Settings

Editor settings

```json
	"editor.codeLens": false,
	"editor.renderWhitespace": "none",
	"editor.autoIndent": true,
	"editor.fontSize": 14,
	"editor.fontFamily": "Inconsolata, Fira code",
	"editor.formatOnPaste": false,
	"editor.formatOnType": true,
	"editor.letterSpacing": 1,
	"editor.tabSize": 2,
	"editor.wordWrap": "off",
```

File settings

```json
	"files.autoSave": "afterDelay",
	"files.autoSaveDelay": 2000,
	"files.exclude": {
		"**/.git": true,
		"**/.DS_Store": true,
		"**/*.js": {
			"when": "$(basename).ts"
		},
		"**/*.js.map": {
			"when": "$(basename)"
		}
	},
	"files.hotExit": "onExit",
	"files.defaultLanguage": "typescript",
	"files.trimTrailingWhitespace": true,
```

Prettier settings

```json
  "prettier.singleQuote": true,
	"prettier.printWidth": 100,
```

## Included

https://marketplace.visualstudio.com/items?itemName=johnpapa.angular-essentials

Here is the list of extensions the pack includes:

[Angular Snippets](https://aka.ms/code-ng-snippets) - Angular snippets that follow the official style guide, for TypeScript, templates, and RxJS.

[Angular Language Service](https://aka.ms/code-ng-ls) - This extension provides a rich editing experience for Angular templates, both inline and external templates. This extension is brought to you by members of the Angular team. It is fantastic at helping write solid code in the html templates.

[Editor Config](https://aka.ms/code-ng-ec) - EditorConfig for VS Code. Great for maintaining consistent editor settings.

[tslint](https://aka.ms/code-ng-tslint) - Integrates the tslint linter for the TypeScript language into VS Code. Extremely helpful at detecting and helping fix TypeScript issues.

[Chrome Debugger](https://aka.ms/code-ng-chrome) - VS Code debugger for Chrome.

[Angular Inline](https://aka.ms/code-ng-inline) - Visual Studio Code language extension for javascript/typescript files that use Angular2.

[Winter is Coming](https://aka.ms/code-ng-winter) theme

[Prettier](https://aka.ms/code-ng-prettier) VS Code plugin for prettier/prettier, which formats code consistently

[Material Icon Theme](https://aka.ms/code-ng-mi) Show material icons in the explorer

[npm](https://aka.ms/code-ng-npm) This extension supports running npm scripts defined in the package.json file and validating the installed modules against the dependencies defined in the package.json.
