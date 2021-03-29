## + React-js-formatting-For-VS-Code 😀 

```json
{
  "editor.wordWrap": "on",
  "editor.defaultFormatter": "esbenp.prettier-vscode", // for formatting
  "editor.formatOnSave": true,  //formate after save
  "[javascript]": {
    "editor.formatOnSave": false 
  },
  "[javascriptreact]": {
    "editor.formatOnSave": false
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.organizeImports": true
  },
  "eslint.alwaysShowStatus": true, // this use for react code formatting
  "javascript.validate.enable": false, 
  "prettier.disableLanguages": ["javascript", "javascriptreact"],
  "bracketPairColorizer.colorMode": "Independent",
  "bracketPairColorizer.independentPairColors": [
    ["()", ["White"], "Red"],
    ["[]", ["Orchid"], "Red"],
    ["{}", ["LightSkyBlue"], "Red"]
  ],
  "emmet.triggerExpansionOnTab": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact" // this use for script emmet ✍️
  },
  "path-autocomplete.extensionOnImport": true, //import path autocomplete 😵
  "path-autocomplete.excludedItems": {
    "**/*.js": {
      "when": "**" //js tag auto autocomplete for .js file 👻
    },
    "**/*.jsx": {
      "when": "**" //js tag auto autocomplete for .jsx file 👻
    }
  }
}
```
