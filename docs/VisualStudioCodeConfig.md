#### Visual Studio Code Config

众所周知现在我们比较流行的开发工具中,特别是在前端开发的过程中,使用最广泛的就是:**Visual Studio Code**

对应的一些插件系统还是比较好用的,由此记录一下我自己的 Visual Studio Code 的组件集合:
```
1. Bracket Pair Colorizer 2
2. Browser Preview
3. Chinese (Simplified) Language Pack for Visual Studio Code
4. Code Runner
5. Code Spell Checker
6. Color Info
7. CSS Peek
8. Debugger for Chrome
9. EditorConfig for VS Code
10. ESLint
11. file-size
12. GitHub Pull Requests
13. gitignore
14. GitLens — Git supercharged
15. GraphQL
16. Image preview
17. JavaScript Booster
18. Jest
19. Live Server
20. Markdown Preview Enhanced
21. MySQL
22. Polacode
23. Prettier - Code formatter
24. Project Mannager
25. Quokka.js
26. REST Client
27. Ruby
28. Settings Sync
29. Todo Tree
30. Vetur
31. Visual Studio IntelliCode
32. VSCode Ruby
33. vscode-drawio  
34. vscode-icons
35. vscode-styled-components
```

我们应该被卸载的Visual Studio Code的插件

1. 功能已经被内置:
- path Intellisense
- Auto Close Tag
- Auto Rename Tag 使用<kbd>F2</kbd>可以进行重构操作
- npm Intellisense 功能已经被内置


2. 维护不积极的
- Color Highlight 替代品 **vscode-colorize**
- TODO Highlight 替代品 **Todo Tree**
- Live Server 
- Bracket Pair Colorizer 2
- indent-rainbow 
- import-cost
- SVG Viewer 替代品 **vscode-svg2**


已经卸载的:
1. Todo Highlight
2. SVG Viewer
3. Path Intellisense
4. IntelliSense for CSS class names in HTML 替代品 **HTML CSS Support**
5. indent-rainbow
6. Import Cost
7. Auto Rename Tag
8. Auto Close Tag



关于 Visual Studio Code 的设置如下所示:
```json
{
  "window.zoomLevel": -1,
  // 以像素为单位控制字号。
  "editor.fontSize": 18,
  // 控制边栏的位置。它可显示在工作台的左侧或右侧。
  "workbench.sideBar.location": "left",
  // 控制工作台中活动栏的可见性。
  "workbench.activityBar.visible": true,
  "git.autofetch": true,
  "explorer.confirmDragAndDrop": false,
  "terminal.integrated.fontFamily": "Consolas",
  // "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\cmd.exe",
  "terminal.integrated.shell.windows": "E:\\DevelopmentUtil\\Git\\usr\\bin\\bash.exe",
  "editor.suggestSelection": "first",
  // "editor.formatOnSave": true,
  "prettier.singleQuote": true,
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "files.associations": {
    "*.cjson": "jsonc",
    "*.wxss": "css",
    "*.wxs": "javascript",
    "*.vue": "vue"
  },
  "emmet.includeLanguages": {
    "wxml": "html"
  },
  "editor.fontFamily": "Source Code Pro,Source Code Variable,Monaco,Consolas,Menlo, 'Courier New', monospace",
  "debug.console.fontFamily": "Source Code Pro",
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  // Vim Config list
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "files.exclude": {
    "**/.classpath": true,
    "**/.project": true,
    "**/.settings": true,
    "**/.factorypath": true
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "breadcrumbs.enabled": true,
  "[typescript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "terminal.external.windowsExec": "D:\\DevelopmentUitl\\git\\bin\\bash.exe",
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "cSpell.enabledLanguageIds": [
    "asciidoc",
    "c",
    "cpp",
    "csharp",
    "css",
    "git-commit",
    "gitignore",
    "go",
    "handlebars",
    "html",
    "jade",
    "java",
    "javascriptreact",
    "json",
    "jsonc",
    "latex",
    "less",
    "markdown",
    "php",
    "plaintext",
    "pug",
    "python",
    "restructuredtext",
    "rust",
    "scala",
    "scss",
    "text",
    "typescript",
    "typescriptreact",
    "yaml",
    "yml"
  ],
  "markdown.preview.fontFamily": "FiraCode-Retina,Source Code Pro, BlinkMacSystemFont, 'Ubuntu', 'Droid Sans', sans-serif",
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "javascript.updateImportsOnFileMove.enabled": "always",
  "files.defaultLanguage": "html",
  "workbench.statusBar.visible": true,
  "files.autoSave": "onFocusChange",
  "editor.find.autoFindInSelection": true,
  "editor.quickSuggestions": {
    "other": true,
    "comments": false,
    "strings": false
  },
  "vsicons.dontShowNewVersionMessage": true,
  "editor.renderWhitespace": "none",
  "editor.renderControlCharacters": true,
  "path-intellisense.autoSlashAfterDirectory": true,
  "path-intellisense.extensionOnImport": true,
  "path-intellisense.showHiddenFiles": true,
  "bracket-pair-colorizer-2.colors": ["Gold", "Orchid", "LightSkyBlue"],
  "vetur.format.scriptInitialIndent": true,
  "vetur.format.styleInitialIndent": true,
  "html-css-class-completion.enableEmmetSupport": true,
  "explorer.confirmDelete": false,
  "gitlens.views.repositories.files.layout": "list",
  "workbench.iconTheme": "vscode-icons",
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[vue]": {
    "editor.defaultFormatter": "octref.vetur"
  },
  "browser-preview.chromeExecutable": "E:\\ToolCollection\\Chrome\\chrome.exe",
  "extensions.ignoreRecommendations": false,
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}
```
