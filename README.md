<p align="center"><img width="200px" src="./Mojito-512.png"></p>

<h1 align="center">Mojito Theme</h1>

<h3 align="center">Sometimes, all you need is Mojito Theme</h3>

<p align="center">Mojito Theme
  <img src="https://github.com/mishatoshi/mojito-vscode-theme/assets/110047849/18da4639-02f5-4990-b5c0-30bc95a2aafa">
</p>
<p align="center">Mojito Juicy Mint Theme
  <img src="https://github.com/mishatoshi/mojito-vscode-theme/assets/110047849/dff3fb3f-8901-4fec-a729-d7d13b5a4377">
</p>
<p align="center">Mojito Blue Ocean Theme
  <img src="https://github.com/mishatoshi/mojito-vscode-theme/assets/110047849/89e22a93-3780-4b73-b53a-7c671fb8d52e">
</p>

## Getting started

You can install this awesome theme through the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=mishatoshi.mojito-vscode-theme&ssr=false#overview).

### Installation

Launch *Quick Open*:

* <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
* <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘P`
* <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

Paste the following command and press `Enter`:

```shell
ext install Mojito Theme
```

And pick the one by **mishatoshi** as author.

## Override theme colors

You can override the Mojito Theme and schemes colors by adding these theme-specific settings to your configuration. For advanced customisation please check the [relative section on the VS Code documentation](https://code.visualstudio.com/docs/getstarted/themes#_customizing-a-color-theme).

### Color Scheme override

#### **Basic example**

```json
"editor.tokenColorCustomizations": {
    "[Mojito Theme]": {
        "comments": "#4DB6AC"
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
                    "foreground": "#4DB6AC"
                }
            }
        ]
    },
},

"workbench.colorCustomizations": {
  "[Mojito Theme]": {
    "editorIndentGuide.activeBackground1": "#AED581"
  }
},
```

<h3 align="center">Don’t worry, be happy😍</h3>
