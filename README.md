# VS Code Settings

```json
{
  // Install extensions that are not setted here: Live Server, Pkl, SQLTools, Postman, Polacode-2022
  "auto-rename-tag.activationOnLanguage": ["html", "xml", "php", "javascript"],

  "asdf.bin": "asdf",

  "better-comments.tags": [
    {
      "tag": "!",
      "color": "#FF2D00",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "?",
      "color": "#3498DB",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "//",
      "color": "#474747",
      "strikethrough": true,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "todo",
      "color": "#FF8C00",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "*",
      "color": "#98C379",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    }
  ],

  "breadcrumbs.enabled": false,

  "code-runner.executorMap": {
    "javascript": "node",
    "php": "C:\\php\\php.exe",
    "python": "python",
    "perl": "perl",
    "ruby": "C:\\Ruby23-x64\\bin\\ruby.exe",
    "go": "go run",
    "html": "\"C:\\Program Files (x86)\\Google\\Chrome\\Application\\chrome.exe\"",
    "java": "cd $dir && javac $fileName && java $fileNameWithoutExt",
    "c": "cd $dir && gcc $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt"
  },

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

  "files.autoSave": "afterDelay",
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "files.associations": {
    "*.dat": "csv (pipe)",
    "*.csv": "csv (semicolon)"
  },

  "git.confirmSync": false,

  "jupyter.interactiveWindow.creationMode": "perFile",

  "material-icon-theme.files.customClones": [
    {
      "name": "rust-mod",
      "base": "rust",
      "color": "blue-400",
      "fileNames": ["mod.rs"]
    },
    {
      "name": "rust-lib",
      "base": "rust",
      "color": "light-green-300",
      "lightColor": "light-green-600",
      "fileNames": ["lib.rs"]
    }
  ],

  "python.terminal.activateEnvironment": false,

  "redhat.telemetry.enabled": true,

  "rust-analyzer.checkOnSave": true,
  "rust-analyzer.trace.server": "verbose",
  "rust-analyzer.assist.termSearch.borrowcheck": true,

  "security.workspace.trust.untrustedFiles": "open",

  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "terminal.integrated.enableVisualBell": true,
  "terminal.integrated.fontSize": 13,

  "vscode-pets.petType": "cat",
  "vscode-pets.petSize": "medium",
  "vscode-pets.position": "explorer",
  "vscode-pets.throwBallWithMouse": true,
  "workbench.editor.showTabs": "multiple",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.editorAssociations": {
    "*.svg": "hediet.vscode-drawio-text"
  },

  "workbench.statusBar.visible": true,
  "workbench.colorTheme": "Catppuccin Mocha",
  "workbench.sideBar.location": "right",
  "workbench.colorCustomizations": {
    "[Catppuccin Mocha]": {
      "activityBar.background": "#191919",
      "editor.background": "#191919",
      "editor.lineHighlightBackground": "#191919",
      "editor.lineHighlightBorder": "#191919",
      "panel.background": "#191919",
      "sideBar.background": "#191919",
      "terminal.background": "#191919"
    }
  },

  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "[python]": {
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.codeActionsOnSave": {
      "source.fixAll": "explicit"
    }
  },
  "vs-kubernetes": {
    "vscode-kubernetes.helm-path-linux": "/home/yuri/.local/state/vs-kubernetes/tools/helm/linux-amd64/helm",
    "vscode-kubernetes.kubectl-path-linux": "/home/yuri/.local/state/vs-kubernetes/tools/kubectl/kubectl",
    "vscode-kubernetes.minikube-path-linux": "/home/yuri/.local/state/vs-kubernetes/tools/minikube/linux-amd64/minikube"
  },
  "todohighlight.isEnable": true,
  "todohighlight.isCaseSensitive": true,
  "todohighlight.keywords": [
    "DEBUG:",
    "REVIEW:",
    {
      "text": "NOTE:",
      "color": "#ffffff",
      "backgroundColor": "#ce0000"
    },
    {
      "text": "HACK:",
      "color": "#ffffff",
      "isWholeLine": false
    },
    {
      "text": "TODO:",
      "color": "#ffffff",
      "border": "nothing",
      "backgroundColor": "#ce0000"
      //other styling properties goes here ...
    }
  ],
  "todohighlight.keywordsPattern": "TODO:|FIXME:", //highlight `TODO:`,`FIXME:` or content between parentheses
  "todohighlight.defaultStyle": {
    "color": "#ffffff",
    "backgroundColor": "#ce0000",
    "cursor": "pointer",
    "border": "nothing",
    "isWholeLine": false
    //other styling properties goes here ...
  },
  "todohighlight.include": [
    "**/*.js",
    "**/*.jsx",
    "**/*.ts",
    "**/*.tsx",
    "**/*.html",
    "**/*.php",
    "**/*.css",
    "**/*.scss"
  ],
  "todohighlight.exclude": [
    "**/node_modules/**",
    "**/bower_components/**",
    "**/dist/**",
    "**/build/**",
    "**/.vscode/**",
    "**/.github/**",
    "**/_output/**",
    "**/*.min.*",
    "**/*.map",
    "**/.next/**"
  ],
  "todohighlight.maxFilesForSearch": 5120,
  "todohighlight.toggleURI": false,
  "hediet.vscode-drawio.resizeImages": null,
  "editor.unicodeHighlight.invisibleCharacters": false,
  "editor.unicodeHighlight.ambiguousCharacters": false,
  "terminal.integrated.enableMultiLinePasteWarning": "auto",
  "accessibility.signals.terminalBell": {
    "sound": "on"
  }
}
```
