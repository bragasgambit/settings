# VS Code Settings

```json
{
  // Install extensions that are not setted here: Live Server, Pkl, SQLTools, Postman, Polacode-2022
  "auto-rename-tag.activationOnLanguage": ["html", "xml", "php", "javascript"],

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

  "workbench.colorTheme": "GitHub Dark Default",
  "workbench.editor.showTabs": "multiple",
  "workbench.editorAssociations": {
    "*.svg": "hediet.vscode-drawio-text"
  },

  "workbench.statusBar.visible": true,
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
  "hediet.vscode-drawio.resizeImages": null
}
```
