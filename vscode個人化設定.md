vscode 個人化設定

command+,可以開啟個人化設定頁面
![image](https://hackmd.io/_uploads/rJP4RTqr6.png)
![image](https://hackmd.io/_uploads/Hk-8CTcSp.png)

然後把下面的資訊複製貼上
```
{
    "editor.cursorStyle": "underline",
    "editor.renderLineHighlight": "all",
    "editor.renderWhitespace": "boundary",
    "editor.smoothScrolling": true,
    "editor.cursorBlinking": "smooth",
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.formatOnType": false,
    "files.insertFinalNewline": true,
    "files.trimTrailingWhitespace": true,
    "workbench.view.alwaysShowHeaderActions": true,
    "breadcrumbs.enabled": true,
    "workbench.editor.highlightModifiedTabs": true,
    "search.useGlobalIgnoreFiles": true,
    "debug.inlineValues": "on",
    "terminal.external.osxExec": "iTerm.app",
    "terminal.integrated.cursorBlinking": true,
    "terminal.integrated.cursorStyle": "underline",
    "update.showReleaseNotes": false,
    "telemetry.telemetryLevel": "off",
    "git.allowForcePush": true,
    "git.alwaysShowStagedChangesResourceGroup": true,
    "git.autofetch": true,
    "git.defaultCloneDirectory": "/Users/ahkui/Desktop/Project",
    "git.fetchOnPull": true,
    "git.ignoreLimitWarning": true,
    "git.ignoreLegacyWarning": true,
    "git.ignoreMissingGitWarning": true,
    "workbench.colorTheme": "Monokai",
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    "vsicons.dontShowNewVersionMessage": true,
    "editor.suggestSelection": "first",
    "workbench.iconTheme": "material-icon-theme",
    "javascript.updateImportsOnFileMove.enabled": "always",
    "dart.debugExternalLibraries": false,
    "dart.debugSdkLibraries": false,
    "dart.previewFlutterUiGuides": true,
    "python.jediEnabled": false,
    "todo-tree.tree.showScanModeButton": false,
    "emmet.showSuggestionsAsSnippets": true,
    "editor.snippetSuggestions": "top",
    "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
    },
    "[dart]": {
        "editor.rulers": [
            80
        ],
        "editor.selectionHighlight": false,
        "editor.suggest.snippetsPreventQuickSuggestions": false,
        "editor.suggestSelection": "first",
        "editor.tabCompletion": "onlySnippets",
        "editor.wordBasedSuggestions": false
    },
    "editor.bracketPairColorization.enabled": true,
    "editor.guides.bracketPairs": "active",
    "python.pythonPath": "/usr/local/bin/python3",
    "editor.linkedEditing": true,
    "liveshare.allowGuestDebugControl": true,
    "liveshare.languages.allowGuestCommandControl": true,
    "liveshare.allowGuestTaskControl": true,
    "terminal.integrated.fontFamily": "'MesloLGS NF'",
    "[python]": {
        "editor.defaultFormatter": "ms-python.python"
    },
    "python.languageServer": "Pylance",
    "phpmd.enabled": false,
    "[php]": {
        "editor.wordSeparators": "`~!@#%^&*()-=+[{]}\\|;:'\",.<>/?",
        "editor.defaultFormatter": "bmewburn.vscode-intelephense-client",
    },
    "[blade]": {
        "editor.autoClosingBrackets": "always",
    },
    "[sql]": {
        "editor.formatOnPaste": false,
        "editor.formatOnSave": false,
    },
    "blade.format.enable": true,
    "emmet.triggerExpansionOnTab": true,
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "editor.wordWrap": "on",
    "editor.largeFileOptimizations": false,
    "go.useLanguageServer": true,
    "go.toolsManagement.autoUpdate": true,
    "go.lintTool": "golangci-lint",
    "go.lintFlags": [
        "--fast"
    ],
    "[json]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "nginx-conf-hint.syntax": "sublime",
    "[dockerfile]": {
        "editor.defaultFormatter": "ms-azuretools.vscode-docker"
    },
    "git-graph.contextMenuActionsVisibility": {},
    "git-graph.customPullRequestProviders": [],
    "git-graph.dialog.addTag.pushToRemote": true,
    "git-graph.dialog.createBranch.checkOut": true,
    "git-graph.dialog.deleteBranch.forceDelete": true,
    "git-graph.dialog.fetchRemote.pruneTags": true,
    "git-graph.dialog.rebase.launchInteractiveRebase": true,
    "git-graph.repository.commits.fetchAvatars": true,
    "gitlens.advanced.messages": {
        "suppressGitVersionWarning": true,
        "suppressRebaseSwitchToTextWarning": true
    },
    "editor.formatOnPaste": false,
    "[jsonc]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "workbench.editorAssociations": {
        "*.ipynb": "jupyter-notebook"
    },
    "gitlens.gitCommands.skipConfirmations": [
        "fetch:command",
        "switch:command"
    ],
    "[yaml]": {
        "editor.defaultFormatter": "redhat.vscode-yaml",
    },
    "material-icon-theme.folders.theme": "specific",
    "notebook.cellToolbarLocation": {
        "default": "right",
        "jupyter-notebook": "left"
    },
    "git.confirmSync": false,
    "redhat.telemetry.enabled": true,
    "security.workspace.trust.untrustedFiles": "open",
    "yaml.format.printWidth": 120,
    "yaml.customTags": [
        "!reference sequence",
        "!And",
        "!Base64",
        "!Cidr",
        "!Equals sequence",
        "!Equals",
        "!FindInMap sequence",
        "!FindInMap sequence",
        "!GetAtt",
        "!GetAZs",
        "!If",
        "!ImportValue",
        "!Join sequence",
        "!Not",
        "!Or",
        "!Ref",
        "!Select sequence",
        "!Select",
        "!Split sequence",
        "!Split",
        "!Sub",
        "!And sequence",
        "!If sequence",
        "!Not sequence",
        "!Or sequence",
        "!FindInMap",
        "!Join",
        "!Sub sequence",
        "!ImportValue sequence"
    ],
    "yaml.validate": true,
    "php.debug.executablePath": "/usr/local/bin/php",
    "php.validate.executablePath": "/usr/local/bin/php",
    "intelephense.environment.phpVersion": "8.1.5",
    "workbench.editor.tabCloseButton": "off",
    "workbench.editor.pinnedTabSizing": "shrink",
    "extensions.ignoreRecommendations": true,
    "editor.formatOnSave": true,
    "terminal.integrated.enableMultiLinePasteWarning": false,
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "files.associations": {
        "*.env": "dotenv",
        "*.ndjson": "ndjson"
    },
    "editor.unicodeHighlight.ambiguousCharacters": false,
    "git.suggestSmartCommit": false,
    "[markdown]": {
        "editor.defaultFormatter": "yzhang.markdown-all-in-one"
    },
    "editor.unicodeHighlight.invisibleCharacters": false,
    "debug.javascript.autoAttachFilter": "disabled",
    "javascript.inlayHints.functionLikeReturnTypes.enabled": true,
    "typescript.inlayHints.functionLikeReturnTypes.enabled": true,
    "python.analysis.inlayHints.functionReturnTypes": true,
    "editor.stickyScroll.enabled": true,
    "terminal.integrated.defaultProfile.osx": "zsh",
    "vs-kubernetes": {
        "vs-kubernetes.crd-code-completion": "enabled",
        "vscode-kubernetes.helm-path.mac": "/Users/ahkui_liew/.vs-kubernetes/tools/helm/darwin-amd64/helm",
        "vscode-kubernetes.kubectl-path.mac": "/Users/ahkui_liew/.vs-kubernetes/tools/kubectl/kubectl",
        "vscode-kubernetes.minikube-path.mac": "/Users/ahkui_liew/.vs-kubernetes/tools/minikube/darwin-amd64/minikube",
        "vs-kubernetes.minikube-show-information-expiration": "2024-01-28T04:28:07.093Z"
    },
    "typescript.updateImportsOnFileMove.enabled": "always",
    "application.shellEnvironmentResolutionTimeout": 60,
    "psalm.analyzedFileExtensions": [
        {
            "scheme": "file",
            "language": "php"
        },
        {
            "scheme": "untitled",
            "language": "php"
        }
    ],
    "[typescriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "git.openRepositoryInParentFolders": "never",
    "psalm.logLevel": "WARN",
    "psalm.unusedVariableDetection": true,
    "psalm.phpExecutablePath": "/usr/local/bin/php",
    "psalm.psalmScriptPath": "/Users/ahkui_liew/.composer/vendor/bin/psalm-language-server",
    "phpsab.executablePathCBF": "/Users/ahkui_liew/.composer/vendor/bin/phpcbf",
    "phpsab.executablePathCS": "/Users/ahkui_liew/.composer/vendor/bin/phpcs",
    "phpsab.debug": true,
    "vue.codeActions.savingTimeLimit": 3000,
    "git-graph.repository.sign.commits": true,
    "git-graph.repository.sign.tags": true,
    "git-graph.repository.commits.showSignatureStatus": true,
    "git.alwaysSignOff": true,
    "git.enableCommitSigning": true,
    "files.autoSave": "onFocusChange",
    "editor.inlineSuggest.enabled": true,
    "go.coverOnSingleTest": true,
    "go.coverOnSingleTestFile": true,
    "go.coverOnSave": true,
    "terminal.integrated.env.linux": {
        "GIT_EDITOR": "code --wait"
    },
    "terminal.integrated.env.osx": {
        "GIT_EDITOR": "code --wait"
    },
    "diffEditor.ignoreTrimWhitespace": false,
    "markdown.extension.orderedList.marker": "one"
}

// ❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️
// cmd + shift + p 快速開啟搜尋之後查 settings json ❤️❤️❤️❤️❤️❤️❤️❤️
// ❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️
```
