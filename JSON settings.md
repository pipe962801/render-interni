{
    "editor.formatOnSave": true,
    "files.autoSave": "afterDelay",
    "emmet.includeLanguages": {
    
    },
    "workbench.colorTheme": "One Dark Pro",
    "editor.fontSize": 16,
    "editor.wordWrap": "on",
    "files.autoSaveDelay": 600,
    "liveServer.settings.donotShowInfoMsg": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode"

    ,"[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
      },
      "diffEditor.ignoreTrimWhitespace": false
}


//Key bindings.JSON

[
  {
    "key": "ctrl+space",
    "command": "cursorLineEnd"
  },
  {
    "key": "ctrl+space",
    "command": "-editor.action.triggerSuggest",
    "when": "editorHasCompletionItemProvider && textInputFocus && !editorReadonly"
  },
  {
    "key": "ctrl+space",
    "command": "-toggleSuggestionDetails",
    "when": "suggestWidgetVisible && textInputFocus"
  },
  {
    "key": "ctrl+alt+l",
    "command": "editor.action.insertSnippet",
    "when": "editorTextFocus",
    "args": {
      "snippet": "console.log(${TM_SELECTED_TEXT}$1)$2;"
    }
  }

]