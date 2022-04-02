# typescript-project-template

## VS Code Plugins

1. EditorConfig
2. ESLint
3. Prettier

## VS Code Settings

1. Show Command Palette (Ctrl + Shift + P)
2. Find `Preferences: Open Settings (JSON)`
3. Add the following lines:

```
    "editor.formatOnSave": true,
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
      },
    "eslint.validate": [
        "javascript"
    ]
```
