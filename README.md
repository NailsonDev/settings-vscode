### Instalação

- Abra o VS Code e use o comando CRTL + P
- Pesquise por ">JSON" e selecione o "Preference: User Open Settings (JSON)"
- Substitua o código pelo de baixo:

```

{
    "workbench.startupEditor": "newUntitledFile",
    "editor.fontSize": 14,
    "editor.lineHeight": 1.8,
    "javascript.suggest.autoImports": true,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "editor.rulers": [
      80,
      120
    ],
    "extensions.ignoreRecommendations": true,
    "typescript.tsserver.log": "off",
    "editor.stickyScroll.enabled": false,
    "workbench.tree.enableStickyScroll": false,
    "files.associations": {
      ".env.*": "dotenv",
      ".prettierrc": "json",
      "*.css": "css",
      ".dev.vars": "dotenv"
    },
    "symbols.files.associations": {
      "*.module.ts": "nest",
      "*.guard.ts": "typescript",
      "*.spec.ts": "ts-test",
      "*.e2e-spec.ts": "ts-test",
      "*.mock.ts": "ts-test",
      "vitest.config.e2e.ts": "vite",
      ".env.development.local": "gear",
      ".env.test.local": "gear",
      ".env.local": "gear",
      ".env.example": "gear"
    },

    "editor.parameterHints.enabled": false,
    "editor.renderLineHighlight": "all",
    "typescript.updateImportsOnFileMove.enabled": "always",
    "editor.suggestSelection": "first",
    "explorer.confirmDelete": false,
    "terminal.integrated.showExitAlert": false,
    "[prisma]": {
      "editor.formatOnSave": true
    },
    "typescript.suggest.autoImports": true,
    "typescript.preferences.preferTypeOnlyAutoImports": true,
    "terminal.integrated.env.osx": {
      "FIG_NEW_SESSION": "1"
    },
    "workbench.editor.labelFormat": "short",
    "editor.fontLigatures": true,
    "emmet.includeLanguages": {
      "javascript": "javascriptreact"
    },
    "emmet.syntaxProfiles": {
      "javascript": "jsx"
    },
    "editor.acceptSuggestionOnCommitCharacter": false,
    "explorer.compactFolders": false,
    "git.enableSmartCommit": true,
    "editor.accessibilitySupport": "off",
    "explorer.confirmDragAndDrop": false,
    "terminal.integrated.fontSize": 13,
    "terminal.integrated.fontFamily": "JetBrains Mono",
    "editor.codeActionsOnSave": {
      "source.fixAll.eslint": "explicit"
    },
    "editor.semanticHighlighting.enabled": false,
    "editor.fontFamily": "JetBrains Mono",
    "editor.tabSize": 2,
    "security.workspace.trust.untrustedFiles": "newWindow",
    "files.exclude": {
      "**\/CVS": true,
      "**\/.DS_Store": true,
      "**\/.hg": true,
      "**\/.svn": true,
      "**\/.git": true,
      ".vscode": true
      // "node_modules": true
    },
    "workbench.iconTheme": "symbols",
    "update.mode": "default",
    "terminal.integrated.gpuAcceleration": "on",
    "terminal.integrated.defaultProfile.osx": "fish",
    "[jsonc]": {
      "editor.defaultFormatter": "vscode.json-language-features"
    },
    "[json]": {
      "editor.defaultFormatter": "vscode.json-language-features"
    },
    "window.commandCenter": false,
    "git.openRepositoryInParentFolders": "always",
    "symbols.hidesExplorerArrows": false,
    "[javascript]": {
      "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    // "workbench.editor.empty.hint": "hidden",
    "update.showReleaseNotes": false,
    "security.promptForLocalFileProtocolHandling": false,
    // "workbench.activityBar.location": "default",
    "editor.hideCursorInOverviewRuler": true,
    "editor.minimap.enabled": false,
    "window.titleBarStyle": "native",
    "explorer.sortOrder": "foldersNestsFiles",
    "explorer.fileNesting.patterns": {
      "package.json": ".eslint*, prettier*, tsconfig*, vite*, pnpm-*, bun.lockb, nest*, package-lock*",
      "tailwind.config.*": "tailwind.config*, postcss.config*",
      ".env.local": ".env*",
      ".env": ".env*"
    },
    "explorer.fileNesting.enabled": true,
    "breadcrumbs.enabled": false,
    "workbench.statusBar.visible": true,
    "editor.tokenColorCustomizations": {
      "textMateRules": []
    },
    "workbench.layoutControl.enabled": false,
    "files.autoSave": "afterDelay",
    "workbench.colorTheme": "Gatito Theme",
  }

```
