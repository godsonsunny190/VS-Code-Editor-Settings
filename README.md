# VS-Code-Editor-Settings{
  "editor.quickSuggestions": {
    "other": true,
    "comments": true,
    "strings": true
  },

  "editor.suggestOnTriggerCharacters": true,
  "editor.tabCompletion": "on",
  "editor.wordBasedSuggestions": "matchingDocuments",

  "javascript.suggest.autoImports": true,
  "typescript.suggest.autoImports": true,

  "eslint.enable": true,

  "files.associations": {
    "*.js": "javascriptreact",
    "*.jsx": "javascriptreact"
  },

  "typescript.validate.enable": true,
  "javascript.validate.enable": true,

  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "javascriptreact": "html"
  },

  "javascript.updateImportsOnFileMove.enabled": "always",
  "typescript.updateImportsOnFileMove.enabled": "always",

  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,

  "editor.accessibilitySupport": "off",

  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "GitHub Dark Default",

  "window.zoomLevel": 1,
  // "window.menuBarVisibility": "toggle",

  "[javascript]": {
    "javascript.preferences.renameMatchingJsxTags": true,
    "editor.maxTokenizationLineLength": 2500
  },

  "extensions.ignoreRecommendations": true,

  "settingsSync.ignoredSettings": [],
  "workbench.settings.applyToAllProfiles": [

  ],

  "editor.fontSize": 13.5,
  "editor.fontFamily": "Cascadia Code, Consolas, monospace",
  "editor.fontWeight": "380",
  "editor.wordWrap": "on",

  "editor.minimap.enabled": false,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorBlinking": "smooth",
  "editor.renderWhitespace": "selection",
  "editor.showFoldingControls": "always",
  "editor.guides.indentation": true,

  "editor.formatOnSave": true,
  "editor.defaultFormatter": "HookyQR.beautify",

  "beautify.language": {
    "js": {
      "type": ["javascript", "json", "jsonc"],
      "filename": [".jshintrc", ".jsbeautifyrc"]
    },
    "css": ["css", "scss"],
    "html": ["htm", "html", "blade"]
  },

  "beautify.config": {
    "indent_size": 2,
    "indent_char": " ",
    "max_preserve_newlines": 2,
    "preserve_newlines": true,
    "wrap_line_length": 100,
    "end_with_newline": true,
    "brace_style": "collapse,preserve-inline",
    "indent_scripts": "normal"
  },

  "files.trimTrailingWhitespace": true,
  "files.autoSave": "afterDelay",

  "git.autofetch": true,
  "git.enableSmartCommit": true,

  "terminal.integrated.rendererType": "dom",
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.fontFamily": "'Inconsolata for Powerline', monospace",

  "workbench.editor.enablePreview": false,
  "workbench.editor.tabSizing": "shrink",
  "workbench.startupEditor": "none",
  "workbench.statusBar.visible": true,

  "breadcrumbs.enabled": true,
  "search.showLineNumbers": true,

  "json.schemas": [],

  "supermaven.enable": {
    "*": true
  }
}