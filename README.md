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

| Extension | Stats |
| --------- | ----- |


| Angular2 Inline | [![Badge for version for Visual Studio Code extension natewallace.angular2-inline](https://vsmarketplacebadge.apphb.com/version/natewallace.angular2-inline.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline&wt.mc_id=vscodepeacock-github-jopapa) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/natewallace.angular2-inline.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/natewallace.angular2-inline.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline) |

| Angular Language Service | [![Badge for version for Visual Studio Code extension Angular.ng-template](https://vsmarketplacebadge.apphb.com/version/Angular.ng-template.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template&wt.mc_id=vscodepeacock-github-jopapa) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/Angular.ng-template.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/Angular.ng-template.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template) |

| Angular Snippets | [![Badge for version for Visual Studio Code extension Angular.ng-template](https://vsmarketplacebadge.apphb.com/version/johnpapa.Angular2.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2&wt.mc_id=vscodepeacock-github-jopapa) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/johnpapa.Angular2.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/johnpapa.Angular2.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2) |

| Angular Console | [![Badge for version for Visual Studio Code extension Angular.ng-template](https://vsmarketplacebadge.apphb.com/version/nrwl.angular-console.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=nrwl.angular-console&wt.mc_id=vscodepeacock-github-jopapa) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/nrwl.angular-console.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=nrwl.angular-console)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/nrwl.angular-console.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=nrwl.angular-console) |

| Chrome Debugger | [![Badge for version for Visual Studio Code extension Angular.ng-template](https://vsmarketplacebadge.apphb.com/version/msjsdiag.debugger-for-chrome.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome&wt.mc_id=vscodepeacock-github-jopapa) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/msjsdiag.debugger-for-chrome.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/msjsdiag.debugger-for-chrome.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome) |

| Editor Config | [![Badge for version for Visual Studio Code extension Angular.ng-template](https://vsmarketplacebadge.apphb.com/version/EditorConfig.EditorConfig.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig&wt.mc_id=vscodepeacock-github-jopapa) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/EditorConfig.EditorConfig.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/EditorConfig.EditorConfig.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) |

| Material Icon Theme | [![Badge for version for Visual Studio Code extension Angular.ng-template](https://vsmarketplacebadge.apphb.com/version/pkief.material-icon-theme.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=pkief.material-icon-theme&wt.mc_id=vscodepeacock-github-jopapa) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/pkief.material-icon-theme.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=pkief.material-icon-theme)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/pkief.material-icon-theme.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=pkief.material-icon-theme) |

| npm | [![Badge for version for Visual Studio Code extension Angular.ng-template](https://vsmarketplacebadge.apphb.com/version/eg2.vscode-npm-script.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script&wt.mc_id=vscodepeacock-github-jopapa) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/eg2.vscode-npm-script.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/eg2.vscode-npm-script.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script) |

| Peacock | [![Badge for version for Visual Studio Code extension Angular.ng-template](https://vsmarketplacebadge.apphb.com/version/johnpapa.vscode-peacock.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock&wt.mc_id=vscodepeacock-github-jopapa) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/johnpapa.vscode-peacock.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/johnpapa.vscode-peacock.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock) |

| Prettier | [![Badge for version for Visual Studio Code extension Angular.ng-template](https://vsmarketplacebadge.apphb.com/version/esbenp.prettier-vscode.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode&wt.mc_id=vscodepeacock-github-jopapa) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/esbenp.prettier-vscode.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/esbenp.prettier-vscode.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) |

| tslint | [![Badge for version for Visual Studio Code extension Angular.ng-template](https://vsmarketplacebadge.apphb.com/version/ms-vscode.vscode-typescript-tslint-plugin.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin&wt.mc_id=vscodepeacock-github-jopapa) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/ms-vscode.vscode-typescript-tslint-plugin.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/ms-vscode.vscode-typescript-tslint-plugin.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin) |

| Winter is Coming | [![Badge for version for Visual Studio Code extension Angular.ng-template](https://vsmarketplacebadge.apphb.com/version/johnpapa.winteriscoming.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=johnpapa.winteriscoming&wt.mc_id=vscodepeacock-github-jopapa) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/johnpapa.winteriscoming.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=johnpapa.winteriscoming)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/johnpapa.winteriscoming.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=johnpapa.winteriscoming) |
