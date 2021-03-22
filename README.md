# PHP/LARAVEL & JS PACK

## Before installing this pack, follow the next steps

1. Open extension search or `CTRL + SHIFT + P > Extensions: Install Extensions`

2. Search for `@builtin php` and disable `PHP Language Features`

3. Open your settings as Json: `CTRL + SHIFT + P > Preferences: Open Settings (json)` and paste the following configs

```json
"intelephense.diagnostics.undefinedTypes": false,
"files.associations": { 
	"*.module": "php" 
},
"blade.format.enable": true,
    "intelephense.diagnostics.undefinedTypes": false,
    "[php]": {
      "editor.formatOnSave": false,
      "editor.formatOnPaste": true,
      "editor.formatOnType": true,
      "editor.tabSize": 4,
      "editor.defaultFormatter": "kokororin.vscode-phpfmt"
    },
    "[blade]": {
      "editor.autoClosingBrackets": "always",
      "editor.formatOnSave": true,
      "editor.formatOnPaste": true,
      "editor.formatOnType": true,
      "editor.tabSize": 4,
      "editor.defaultFormatter": "onecentlin.laravel-blade"
    },
```
