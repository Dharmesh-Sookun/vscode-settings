# VS Code Settings

# Font

* [Menlo](https://www.cufonfonts.com/font/menlo)

## Themes/Color

* Current theme:
  * [Just Black](https://marketplace.visualstudio.com/items?itemName=nur.just-black)

## Extensions

These are the extensions I have installed:

* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
  * Material Design Icons for Visual Studio Code
* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  * Integrates ESLint JS
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  * Prettier is an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.
* [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
  * This extension quickly searches (using ripgrep) your workspace for comment tags like TODO and FIXME, and displays them in a tree view in the activity bar. The view can be dragged out of the activity bar into the explorer pane (or anywhere else you would prefer it to be). Clicking a TODO within the tree will open the file and put the cursor on the line containing the TODO. Found TODOs can also be highlighted in open files.
* [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
  * Quokka.js is a developer productivity tool for rapid JavaScript / TypeScript prototyping. Runtime values are updated and displayed in your IDE next to your code, as you type.
* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
  * Launch a local development server with live reload feature for static & dynamic pages.
* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  * Automatically rename paired HTML/XML tag, same as Visual Studio IDE does.
* [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
  * A Visual Studio Code extension that provides CSS class name completion for the HTML class attribute based on the definitions found in your workspace or external files referenced through the link element.
* [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
  * This extension colorizes the indentation in front of your text, alternating four different colors on each step.
* [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
  * This extension extends HTML and ejs code editing with Go To Definition and Go To Symbol in Workspace support for css/scss/less (classes and IDs) found in strings within the source code.
* [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
  * This extension contains code snippets for JavaScript in ES6 syntax for Vs Code editor (supports both JavaScript and TypeScript).
* [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
  * A Visual Studio Code extension with rich support for the Python language (for all actively supported versions of the language: >=3.7), including features such as IntelliSense (Pylance), linting, debugging, code navigation, code formatting, refactoring, variable explorer, test explorer, and more!
* [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)
  * Pylance is an extension that works alongside Python in Visual Studio Code to provide performant language support.

# Settings

```json
{
  "files.autoSave": "afterDelay",
  "auto-rename-tag.activationOnLanguage": ["*"],
  "editor.formatOnSave": true,
  "workbench.iconTheme": "material-icon-theme",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.snippetSuggestions": "top",
  "editor.fontLigatures": true,
  "editor.fontSize": 16,
  "quokka.colors": {
    "covered": "#62b455",
    "errorPath": "#ffa0a0",
    "errorSource": "#fe536a",
    "notCovered": "#cccccc",
    "partiallyCovered": "#d2a032"
  },
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "editor.stablePeek": true,
  "explorer.openEditors.visible": 0,
  "python.linting.enabled": false,
  "jupyter.alwaysTrustNotebooks": true,
  "workbench.editorAssociations": {
    "*.ipynb": "jupyter.notebook.ipynb"
  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": ["comment", "comment.block"],
        "settings": {
          "fontStyle": "italic",
          "foreground": "#ff1493"
        }
      },
      {
        "scope": [
          "keyword.operator.logical",
          "keyword.operator.arithmetic",
          "keyword.operator.assignment",
          "keyword.operator.bitwise"
        ],
        "settings": {
          "fontStyle": ""
        }
      }
    ]
  },
  "php.validate.executablePath": "C:/xampp/php/php.exe",
  "files.eol": "\n",
  "liveServer.settings.donotShowInfoMsg": true,
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.tabSize": 2,
  "liveServer.settings.donotVerifyTags": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "editor.semanticHighlighting.enabled": false,
  "workbench.preferredHighContrastColorTheme": "Visual Studio Dark",
  "prettier.singleQuote": true,
  "javascript.preferences.quoteStyle": "single",
  "typescript.preferences.quoteStyle": "single",
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "terminal.integrated.profiles.windows": {
    "PowerShell": {
      "source": "PowerShell",
      "icon": "terminal-powershell"
    },
    "Command Prompt": {
      "path": [
        "${env:windir}\\Sysnative\\cmd.exe",
        "${env:windir}\\System32\\cmd.exe"
      ],
      "args": [],
      "icon": "terminal-cmd"
    },
    "Git Bash": {
      "source": "Git Bash"
    },
    "Windows PowerShell": {
      "path": "C:\\WINDOWS\\System32\\WindowsPowerShell\\v1.0\\powershell.exe"
    }
  },
  "[python]": {
    "editor.formatOnType": true
  },
  "workbench.colorTheme": "Just Black",
  "editor.fontFamily": "Menlo, Anonymous Pro, Consolas, 'Courier New', monospace",
  "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font Mono",
  "terminal.integrated.lineHeight": 1.5
}
```

