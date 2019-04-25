# Angular Essentials - Extension Pack for VS Code

[![Badge for version for Visual Studio Code extension johnpapa.angular-essentials](https://vsmarketplacebadge.apphb.com/version/johnpapa.angular-essentials.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=johnpapa.angular-essentials&wt.mc_id=vscodepeacock-github-jopapa) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/johnpapa.angular-essentials.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=johnpapa.angular-essentials)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/johnpapa.angular-essentials.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=johnpapa.angular-essentials) [![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?color=blue&style=flat-square)](http://opensource.org/licenses/MIT)

This extension pack for Visual Studio Code adds extensions that are amazingly useful for Angular development.

See the [CHANGELOG](CHANGELOG.md) for the latest changes

I am often asked, "What are you favorite VS Code extensions for Angular?". I decided it was time to share them via an extension pack.

Introducing my [Angular Essentials extension pack for VS Code](https://marketplace.visualstudio.com/items?itemName=johnpapa.angular-essentials). By installing this extension pack you get a set of great extensions that are helpful with Angular development. You can check out the initial list below.

> As web tools evolve, the usefulness of extensions come and go. I reserve the right to update the extension pack's contents up to my own discretion.

## Recommended Settings

Here are some of my recommended settings. These are optional, but I get asked a lot for them, so here they are.

### Editor settings

```json
  "editor.autoIndent": true,
  "editor.codeActionsOnSave": {
    "source.organizeImports": false
  },
  "editor.codeLens": false,
  "editor.cursorBlinking": "solid",
  "editor.cursorSmoothCaretAnimation": true,
  "editor.cursorStyle": "line",
  "editor.fontSize": 16,
  "editor.fontFamily": "Dank Mono, Operator Mono, Fira Code, Inconsolata, Menlo",
  "editor.fontLigatures": true,
  "editor.formatOnPaste": true,
  "editor.formatOnType": false,
  "editor.formatOnSave": true,
  "editor.letterSpacing": 0.5,
  "editor.lineHeight": 25,
  "editor.minimap.enabled": false,
  "editor.renderWhitespace": "none",
  "editor.tabCompletion": "on",
  "editor.tabSize": 2,
  "editor.wordWrap": "off",
```

### File settings

```json
"files.autoSave": "afterDelay",
"files.autoSaveDelay": 1000,
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

### Prettier settings

```json
"prettier.singleQuote": true,
"prettier.printWidth": 100,
```

### Peacock Settings

These are my preferred settings for Peacock. I also choose the "favorite" of "Angular Red" for my Angular apps.

```json
  "peacock.affectActivityBar": true,
  "peacock.affectStatusBar": true,
  "peacock.affectTitleBar": false,
  "peacock.keepBadgeColor": false,
  "peacock.keepForegroundColor": false,
  "peacock.favoriteColors": [
    {
      "name": "Angular Red",
      "value": "#b52e31"
    },
    {
      "name": "Auth0 Orange",
      "value": "#eb5424"
    },
    {
      "name": "Azure Blue",
      "value": "#007fff"
    },
    {
      "name": "Gatsby Purple",
      "value": "#639"
    },
    {
      "name": "JavaScript Yellow",
      "value": "#f9e64f"
    },
    {
      "name": "Mandalorian Blue",
      "value": "#1857a4"
    },
    {
      "name": "Node Green",
      "value": "#215732"
    },
    {
      "name": "React Blue",
      "value": "#00b3e6"
    },
    {
      "name": "Something Different",
      "value": "#832561"
    },
    {
      "name": "Vue Green",
      "value": "#42b883"
    }
  ],
  ```

## Included

Here is the list of extensions the pack includes:

[Angular Inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline&wt.mc_id=vscodeangularessentials-github-jopapa) - Visual Studio Code language extension for javascript/typescript files that use Angular2.

[Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template&wt.mc_id=vscodeangularessentials-github-jopapa) - This extension provides a rich editing experience for Angular templates, both inline and external templates. This extension is brought to you by members of the Angular team. It is fantastic at helping write solid code in the html templates.

[Angular Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2&wt.mc_id=vscodeangularessentials-github-jopapa) - Angular snippets that follow the official style guide, for TypeScript, templates, and RxJS.

[Chrome Debugger](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome&wt.mc_id=vscodeangularessentials-github-jopapa) - VS Code debugger for Chrome.

[Editor Config](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig&wt.mc_id=vscodeangularessentials-github-jopapa) - EditorConfig for VS Code. Great for maintaining consistent editor settings.

[Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=pkief.material-icon-theme&wt.mc_id=vscodeangularessentials-github-jopapa) Show material icons in the explorer

[npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script&wt.mc_id=vscodeangularessentials-github-jopapa) This extension supports running npm scripts defined in the package.json file and validating the installed modules against the dependencies defined in the package.json.

[Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock&wt.mc_id=vscodeangularessentials-github-jopapa) This extension subtly changes the workspace color of your workspace. Ideal when you have multiple VS Code instances and you want to quickly identify which is which.

[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode&wt.mc_id=vscodeangularessentials-github-jopapa) VS Code plugin for prettier/prettier, which formats code consistently

[tslint](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin&wt.mc_id=vscodeangularessentials-github-jopapa) - Adds tslint to VS Code using the TypeScript TSLint language service plugin.

[Winter is Coming](https://marketplace.visualstudio.com/items?itemName=johnpapa.winteriscoming&wt.mc_id=vscodeangularessentials-github-jopapa) theme
