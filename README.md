# VS Code Settings

{
  "breadcrumbs.enabled": false,

  "editor.fontSize": 14,
  "editor.wordWrap": "on",
  "editor.defaultFormatter": "esbenp.prettier-vscode",

  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "[python]": {
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "charliermarsh.ruff",
    "editor.codeActionsOnSave": {
      "source.fixAll": "explicit"
    }
  },

  "editor.fontLigatures": true,
  "editor.formatOnSave": true,
  "editor.linkedEditing": true,

  "explorer.confirmDelete": false,
  "explorer.compactFolders": false,

  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "files.autoSave": "afterDelay",

  "terminal.integrated.fontSize": 13,

  "workbench.statusBar.visible": false,
  "workbench.editor.showTabs": "none",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "GitHub Dark Default",
  "workbench.preferredDarkColorTheme": "GitHub Dark Default",
  "workbench.preferredLightColorTheme": "GitHub Light Default",
  "workbench.colorCustomizations": {
    "[Night Owl (No Italics)]": {
      "activityBar.background": "#000C1D",
      "activityBar.border": "#102a44",
      "editorGroup.border": "#102a44",
      "sideBar.background": "#001122",
      "sideBar.border": "#102a44",
      "sideBar.foreground": "#8BADC1"
    },
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
  "explorer.confirmDragAndDrop": false,
  "accessibility.signals.terminalBell": {
    "sound": "on"
  },
  "python.terminal.activateEnvironment": false,
  "terminal.integrated.enableVisualBell": true,
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "git.confirmSync": false,
  "redhat.telemetry.enabled": true,
  "rust-analyzer.trace.extension": true,
  "rust-analyzer.trace.server": "verbose",
  "security.workspace.trust.untrustedFiles": "open",
  "gitlens.currentLine.enabled": false,
  "jupyter.interactiveWindow.creationMode": "perFile",
  "workbench.sideBar.location": "right"
}
