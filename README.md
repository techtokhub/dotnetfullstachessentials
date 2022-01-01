# .Net full stack Essentials - Extension Pack for VS Code
 [![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?color=blue&style=flat-square)](http://opensource.org/licenses/MIT)

This extension pack for Visual Studio Code adds extensions that are amazingly useful for dotnet fullstack development

See the [CHANGELOG](CHANGELOG.md) for the latest changes

I am often searched all my favorite VS Code extensions. So I decided it was time to share them via an extension pack.

> As web tools evolve, the usefulness of extensions come and go. I reserve the right to update the extension pack's contents up to my own discretion.

## Recommended Settings

Here are some of my recommended settings. These are optional, but I get asked a lot for them, so here they are.

### Editor settings

```json
  "editor.autoIndent": "full",
  "editor.codeLens": false,
  "editor.cursorBlinking": "solid",
  "editor.cursorSmoothCaretAnimation": true,
  "editor.cursorStyle": "line",
  "editor.fontSize": 16,
  "editor.fontFamily": "'FiraCodeiScript-Bold', Dank Mono, Operator Mono, Fira Code, Inconsolata",
  "editor.fontLigatures": true,
  "editor.formatOnPaste": true,
  "editor.formatOnType": false,
  "editor.formatOnSave": true,
  "editor.letterSpacing": 0.5,
  "editor.lineHeight": 25,
  "editor.minimap.enabled": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.suggestSelection": "first",
  "editor.tabCompletion": "on",
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "scope": [
        //following will be in italic (=FlottFlott)
        "comment",
        "entity.name.type.class", //class names
        "entity.other.attribute-name", //HTML Attributes
        "keyword", //import, export, return…
        "constant", //String, Number, Boolean…, this, super
        "storage.modifier", //static keyword
        "storage.type.class.js", //class keyword
      ],
      "settings": {
        "fontStyle": "italic"
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
        "fontStyle": ""
      }
    }
  ]
}
```
### File settings

```json
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 1000,
  "files.hotExit": "onExit",
  "files.defaultLanguage": "",
  "files.trimTrailingWhitespace": true,
```

### Prettier settings

```json
  "prettier.printWidth": 120,
  "prettier.bracketSpacing": true,
  "prettier.singleQuote": true,
```

## Included

This extension pack includes the following extensions:

| Extension                | Stats                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Angular Snippets         | [![Badge for version for Visual Studio Code extension](https://vsmarketplacebadge.apphb.com/version-short/johnpapa.Angular2.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2&WT.mc_id=javascript-0000-jopapa) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/johnpapa.Angular2.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2&WT.mc_id=javascript-0000-jopapa) [![Rating](https://vsmarketplacebadge.apphb.com/rating-short/johnpapa.Angular2.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2&WT.mc_id=javascript-0000-jopapa)                                                                   |