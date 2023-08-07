<p align="center"><img width="250px" src="./mojito-theme-512.png"></p>

<h1 align="center">Sometimes, all you need is Mojito Theme</h1>

<p align="center">HTML
  <img src="https://github.com/mishatoshi/mojito-vscode-theme/assets/110047849/413f5aab-bc8b-427a-b39e-a7216c830ff5">
</p>
<p align="center">CSS
  <img src="https://github.com/mishatoshi/mojito-vscode-theme/assets/110047849/659735ec-45f5-4d91-88da-0d0d2dd88e86">
</p>
<p align="center">JS
  <img src="https://github.com/mishatoshi/mojito-vscode-theme/assets/110047849/a48fbcc5-724a-4f8e-80ca-4973684d6a8a">
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

<h2 align="center">Don’t worry, be happy😍</h2>
