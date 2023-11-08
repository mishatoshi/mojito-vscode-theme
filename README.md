<div align="center">
  <img src="./logo-512.png" width="150px" height="150px">
</div>

<h1 align="center" style="color:#FFC107;">Mojito Theme Collection for Visual Studio Code</h1>

<h3 align="center">🍸 Five beautiful dark themes for comfortable work. Choose your dark theme:</h3>

<div align="center" style="margin-bottom:20px;">
  <div>Mojito Theme</div>
  <div>Mojito Juicy Mint Theme</div>
  <div>Mojito Blue Ocean Theme</div>
  <div>Mojito Dark Theme</div>
  <div>Mojito Deep Purple Theme</div>
</div>

<p align="center">
  <img src="https://github.com/mishatoshi/mojito-vscode-theme/assets/110047849/e2983788-9451-4505-a757-9a1a210b8e47">
</p>

## Getting started

You can install this awesome theme through the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=mishatoshi.mojito-vscode-theme&ssr=false#overview).

### Installation

1. Launch *Quick Open*:

    * <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <span>Linux</span> `Ctrl+P`
    * <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <span>Mac OS</span> `⌘P`
    * <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <span>Windows</span> `Ctrl+P`

1. Paste the following command and press `Enter`:

    ``` shell
    ext install Mojito Theme Collection
    ```

1. And pick the one by **mishatoshi** as author.

1. Then [select a theme](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme):

    * `Mojito Theme`
    * `Mojito Juicy Mint Theme`
    * `Mojito Blue Ocean Theme`
    * `Mojito Dark Theme`
    * `Mojito Deep Purple Theme`

## Override theme colors

You can override the Mojito Theme Collection and schemes colors by adding these theme-specific settings to your configuration. For advanced customisation please check the [relative section on the VS Code documentation](https://code.visualstudio.com/docs/getstarted/themes#_customizing-a-color-theme).

### Color Scheme override

#### **Basic example**

```json
"editor.tokenColorCustomizations": {
    "[Mojito Theme]": {
        "comments": "#3EA89F"
    }
},
```

#### **Advanced example**

```json
"editor.tokenColorCustomizations": {
    "[Mojito Theme]": {
        "textMateRules": [
            {
                "scope": [
                    "comment",
                    "comment punctuation.definition.comment"
                ],
                "settings": {
                    "foreground": "#3EA89F"
                }
            }
        ]
    },
},

"workbench.colorCustomizations": {
  "[Mojito Theme]": {
    "editorIndentGuide.activeBackground1": "#B2E26A"
  }
},
```

## Other versions

* Windows Terminal, PowerShell, CMD: [https://github.com/mishatoshi/mojito-windows-terminal](https://github.com/mishatoshi/mojito-windows-terminal)
* Firefox:
  * Mojito Theme [https://addons.mozilla.org/ru/firefox/addon/mojito-theme/](https://addons.mozilla.org/ru/firefox/addon/mojito-theme/)
  * Mojito Juicy Mint Theme [https://addons.mozilla.org/ru/firefox/addon/mojito-juicy-mint/](https://addons.mozilla.org/ru/firefox/addon/mojito-juicy-mint/)
  * Mojito Blue Ocean Theme [https://addons.mozilla.org/ru/firefox/addon/mojito-blue-ocean/](https://addons.mozilla.org/ru/firefox/addon/mojito-blue-ocean/)
  * Mojito Dark Theme [https://addons.mozilla.org/ru/firefox/addon/mojito-dark/](https://addons.mozilla.org/ru/firefox/addon/mojito-dark/)
  * Mojito Deep Purple Theme [https://addons.mozilla.org/ru/firefox/addon/mojito-deep-purple/](https://addons.mozilla.org/ru/firefox/addon/mojito-deep-purple/)
* Flow Launcher [https://github.com/mishatoshi/mojito-flowlauncher-theme](https://github.com/mishatoshi/mojito-flowlauncher-theme)

## License

[MIT License](./LICENSE)

<h3 align="center">Don’t worry, be happy😍</h3>
