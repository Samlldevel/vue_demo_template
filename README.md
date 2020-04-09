# vue_test_template

## 说明

为了更方便的写 vue demo ，减少每次建立写 demo 在建立路由引入等环节花费的时间
现在只要在 `@/view/main-page` 中建立组件,即可自动读取，并生成按钮，可展示对应组件的页面。

## 代码风格配置

使用前，老规矩

```
npm install
```

在 `setting.json` 中配置代码风格，需要安装 `eslint`、`Prettier - Code formatter`、`Vetur`等插件

```
{
 {
  "prettier.singleQuote": true,
  "editor.fontSize": 16,
  "editor.tabSize": 2,
  "editor.formatOnSave": true,
  "editor.insertSpaces": true,
  "editor.minimap.enabled": false,
  "editor.wrappingIndent": "indent",
  "editor.dragAndDrop": false,
  "editor.showFoldingControls": "always",
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.snippetSuggestions": "top",
  "vetur.validation.style": false,
  "vetur.validation.script": false,
  "vetur.validation.template": false,
  "vetur.format.defaultFormatter.html": "js-beautify-html",
  "javascript.format.insertSpaceBeforeFunctionParenthesis": true,
  "vetur.format.defaultFormatterOptions": {
    "js-beautify-html": {
      "wrap_attributes": "force-aligned"
    },
    "prettier": {
      "semi": false,
      "singleQuote": true
    }
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "explorer.confirmDelete": false,
  "editor.suggestSelection": "first",
  "window.zoomLevel": 0,
  "eslint.format.enable": true,
  "prettier.trailingComma": "none",
  "prettier.jsxSingleQuote": true,
  "[vue]": {
    "editor.defaultFormatter": "octref.vetur"
  },
  "prettier.semi": false
}
```
