# VS Code Extensions & Settings

# Launch VS Code from Terminal.

I found it easy to launch VS Code from the terminal, as it opens a VS Code workspace from the folder that I am currently in.

1. Launch VS Code.
2. Open the Command Palette (Cmd+Shift+P) and type 'shell command' to find the Shell Command: Install 'code' command in PATH command.

# Font

* [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous-pro)

## Themes/Color

* [Just Black](https://marketplace.visualstudio.com/items?itemName=nur.just-black)

## Extensions

* Theme / Editor Experience
  * [FontSize ShortCuts](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts)
    * Change the font size with keyboard shortcuts.
  * [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
    * Nice / colorful icons for many different file types
  * [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
    * Integrates ESLint JS
  * [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    * Automatically format javascript, JSON, CSS, Sass
  * [PostCSS Intellisense and Highlighting](https://marketplace.visualstudio.com/items?itemName=vunguyentuan.vscode-postcss)
    * Works better than the other more popular one of a similar name.
  * [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
    * Spell check markdown, comments and variable names.
* Useful Tools
  * [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)
    * Auto generate TypeScript (and other languages) types from JSON data.
* Languages and Libraries
  * [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=styled-components.vscode-styled-components)
     * Syntax highlighting for styled-components.
  * [htmx-tags](https://marketplace.visualstudio.com/items?itemName=otovo-oss.htmx-tags)
    * Provides HTMX tag completion in HTML files in VSCode


# Settings

1. Copy the settings below
2. Launch VS Code
3. Open the Command Palette (Cmd+Shift+P) and search for 'Open User Settings (JSON)'
4. Paste the settings and save

```json
{
  "cSpell.enableFiletypes": ["mdx"],
  "cSpell.enabled": true,
  "diffEditor.ignoreTrimWhitespace": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[handlebars]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.detectIndentation": true,
  "editor.fontFamily": "Anonymous Pro",
  "editor.fontLigatures": true,
  "editor.fontSize": 13,
  "editor.formatOnPaste": false,
  "editor.formatOnSave": true,
  "editor.inlineSuggest.enabled": true,
  "editor.lineHeight": 0,
  "editor.linkedEditing": true,
  "editor.minimap.enabled": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.snippetSuggestions": "top",
  "editor.suggestSelection": "first",
  "editor.tabSize": 2,
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": ["keyword.operator", "punctuation.separator"],
        "settings": {
          "fontStyle": ""
        }
      },
      {
        "scope": [
          "comment",
          "comment.block",
          "comment.line",
          "comment.block.documentation",
          "punctuation.definition.comment"
        ],
        "settings": {
          "fontStyle": "italic",
          "foreground": "#0F0"
        }
      },
      {
        "name": "envKeys",
        "scope": "string.quoted.double.env,source.env,constant.numeric.env",
        "settings": {
          "foreground": "#19354900"
        }
      }
    ]
  },
  "editor.unicodeHighlight.invisibleCharacters": false,
  "emmet.showAbbreviationSuggestions": false,
  "eslint.enable": true,
  "eslint.validate": ["vue", "react", "typescript", "html", "javascript"],
  "explorer.openEditors.visible": 1,
  "extensions.ignoreRecommendations": true,
  "files.autoSave": "onWindowChange",
  "git.autofetch": true,
  "git.confirmSync": false,
  "git.enableSmartCommit": true,
  "git.openRepositoryInParentFolders": "never",
  "markdown.preview.fontSize": 36,
  "search.exclude": {
    "**/*.code-search": true,
    "**/bower_components": true,
    "**/node_modules": true
  },
  "search.useIgnoreFiles": false,
  "terminal.integrated.fontSize": 14,
  "vsicons.dontShowNewVersionMessage": true,
  "window.zoomLevel": 4,
  "workbench.colorTheme": "Just Black",
  "workbench.editor.labelFormat": "medium",
  "workbench.iconTheme": "vscode-icons",
  "workbench.sideBar.location": "left",
  "workbench.startupEditor": "newUntitledFile",
  "workbench.statusBar.visible": false,
  "yaml.customTags": [
    "!And",
    "!And sequence",
    "!If",
    "!If sequence",
    "!Not",
    "!Not sequence",
    "!Equals",
    "!Equals sequence",
    "!Or",
    "!Or sequence",
    "!FindInMap",
    "!FindInMap sequence",
    "!Base64",
    "!Join",
    "!Join sequence",
    "!Cidr",
    "!Ref",
    "!Sub",
    "!Sub sequence",
    "!GetAtt",
    "!GetAZs",
    "!ImportValue",
    "!ImportValue sequence",
    "!Select",
    "!Select sequence",
    "!Split",
    "!Split sequence"
  ],
  "editor.largeFileOptimizations": false,
  "editor.unicodeHighlight.nonBasicASCII": false
}

```
