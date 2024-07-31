# VS Code Settings

```json
{
  "breadcrumbs.enabled": false,

  "editor.fontSize": 15,
  "editor.wordWrap": "on",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.fontLigatures": true,
  "editor.formatOnSave": true,
  "editor.linkedEditing": true,
  "editor.snippetSuggestions": "top",

  "explorer.compactFolders": false,
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,

  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "files.autoSave": "afterDelay",

  "git.confirmSync": false,

  "jupyter.interactiveWindow.creationMode": "perFile",

  "python.terminal.activateEnvironment": false,

  "redhat.telemetry.enabled": true,

  "rust-analyzer.trace.extension": true,
  "rust-analyzer.trace.server": "verbose",

  "security.workspace.trust.untrustedFiles": "open",

  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "terminal.integrated.enableVisualBell": true,
  "terminal.integrated.fontSize": 13,

  "workbench.colorTheme": "GitHub Dark Default",
  "workbench.editor.showTabs": "none",
  "workbench.statusBar.visible": false,
  "workbench.iconTheme": "material-icon-theme",
  "workbench.preferredDarkColorTheme": "GitHub Dark Default",
  "workbench.preferredLightColorTheme": "GitHub Light Default",
  "workbench.sideBar.location": "right",
  "workbench.colorCustomizations": {
    "[GitHub Dark Default]": {
      "activityBar.background": "#000",
      "editor.background": "#000",
      "editor.lineHighlightBackground": "#0000",
      "editor.lineHighlightBorder": "#0000",
      "editorWhitespace.foreground": "#59A5FC",
      "panel.background": "#000",
      "sideBar.background": "#000",
      "terminal.background": "#000",
      "terminal.foreground": "#fff"
    },
    "[GitHub Light Default]": {
      "activityBar.background": "#fff",
      "editor.background": "#fff",
      "editor.lineHighlightBackground": "#fff0",
      "editor.lineHighlightBorder": "#fff0",
      "editorWhitespace.foreground": "#1167D7",
      "panel.background": "#fff",
      "sideBar.background": "#fff",
      "terminal.background": "#fff",
      "terminal.foreground": "#000"
    }
  },

  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "[python]": {
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "charliermarsh.ruff",
    "editor.codeActionsOnSave": {
      "source.fixAll": "explicit"
    }
  }
}

```
