## vscode常用配置

```json
// 用到的插件有esLint、Prettier
{
  // vscode 原生配置项
  "editor.tabSize": 2,		// tab制表符相当于的空格大小
  "editor.wordWrap": "on",	// 控制是否换行
  "editor.formatOnSave": true,	// 控制是否保存时格式化代码
  "javascript.format.insertSpaceBeforeFunctionParenthesis": true,	// 函数括号前后添加空格
  "git.confirmSync": true,	// 显示空格点点
  // esLint 相关配置
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "eslint.autoFixOnSave": true,
  // prettier 相关配置
  "prettier.semi": false,	// 控制是否在行尾添加分号
  "prettier.bracketSpacing": false,	  // 控制是否在对象{}前后添加空格
}

```

一些用的到但是不常更改的设置

```javascript
// 设置中搜索折叠 > Folding Strategy : indentation , 用于控制折叠方式，显示成<div></div>的方式
```

