<p align="center"><img width="200px" src="./Mojito-512.png"></p>

<h1 align="center">Mojito Theme Collection</h1>

<h3 align="center">🍸 The Mojito Theme Collection includes five color themes for comfortable work</h3>

<p align="center">
  <img src="https://github.com/mishatoshi/mojito-vscode-theme/assets/110047849/15576e8a-9709-4299-ba34-f6957d3ce56c">
</p>

## Getting started

You can install this awesome theme through the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=mishatoshi.mojito-vscode-theme&ssr=false#overview).

### Installation

1. Launch *Quick Open*:

* <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <span>Linux</span> `Ctrl+P`
* <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <span>Mac OS</span> `⌘P`
* <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <span>Windows</span> `Ctrl+P`

2. Paste the following command and press `Enter`:

   ``` shell
   ext install Mojito Theme Collection
   ```
3. And pick the one by **mishatoshi** as author.

4. Then [select a theme](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme):

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
    "editorIndentGuide.activeBackground1": "#AED581"
  }
},
```

<h3 align="center">Don’t worry, be happy😍</h3>
