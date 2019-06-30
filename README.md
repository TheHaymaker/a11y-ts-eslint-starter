# Starter Project utilizing CREATE-REACT-APP

## Intention

- Have a go-to starter template for new react projects
- A11y-ready
- Eslint configuration baked-in
- Typescript config baked-in
- Cut down on research and configuration when starting new projects

## VSCode setting reference for speedy integration

```js
{
  "editor.formatOnSave": true,
  "[javascript]": {
    "editor.formatOnSave": false
  },
  "[javascriptreact]": {
    "editor.formatOnSave": false
  },
  "[typescript]": {
    "editor.formatOnSave": false
  },
  "[typescriptreact]": {
    "editor.formatOnSave": false
  },
  "eslint.autoFixOnSave": true,
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    {
      "language": "typescript",
      "autoFix": true
    },
    {
      "language": "typescriptreact",
      "autoFix": true
    }
  ],
  "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
  "terminal.external.windowsExec": "C:\\windows\\System32\\bash.exe",
  "terminal.integrated.shellArgs.windows": ["-l"],
  "workbench.colorTheme": "Electron",
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "editor.fontFamily": "'Dank Mono', Consolas, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "window.zoomLevel": 2,
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          //following will be in italic (=FlottFlott)
          "comment",
          "entity.name.type.class", //class names
          "keyword", //import, export, return…
          "constant", //String, Number, Boolean…, this, super
          "storage.modifier", //static keyword
          "storage.type.class.js", //class keyword
          "variable.parameter"
          // "entity.name.function"
        ],
        "settings": {
          "fontStyle": "Dank Mono italic"
        }
      },
      {
        "scope": [
          //following will be excluded from italics (VSCode has some defaults for italics)
          "invalid",
          "keyword.operator",
          "constant.numeric.css",
          "keyword.other.unit.px.css",
          "constant.numeric.decimal.js",
          "constant.numeric.json"
        ],
        "settings": {
          "fontStyle": "Dank Mono"
        }
      }
    ]
  },
  "editor.tabSize": 2,
  "prettier.eslintIntegration": true,
  "editor.cursorBlinking": "phase",
  "editor.cursorStyle": "line",
  "editor.multiCursorMergeOverlapping": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.cursorWidth": 2,
  "editor.minimap.renderCharacters": false,
  "editor.renderLineHighlight": "gutter",
  "files.trimFinalNewlines": true,
  "files.insertFinalNewline": true,
  "search.showLineNumbers": true,
  "emmet.triggerExpansionOnTab": true,
  "emmet.showSuggestionsAsSnippets": true,
  "editor.suggest.snippetsPreventQuickSuggestions": false,
  "git.path": "C:\\Program Files\\git\\cmd\\git.exe",
  "git.alwaysShowStagedChangesResourceGroup": true,
  "breadcrumbs.enabled": true,
  "explorer.confirmDelete": false,
  "editor.wordWrap": "on",
  "workbench.iconTheme": "material-icon-theme"
}
```
