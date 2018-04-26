
#vscode

`// 将设置放入此文件中以覆盖默认设置
{
    //文字大小
    "editor.fontSize": 18,
    //界面主题
    "workbench.colorTheme": "One Monokai",
    //图标主题
    "workbench.iconTheme": "vscode-icons",
    "vsicons.dontShowNewVersionMessage": true,
    //live server 不显示信息消息
    "liveServer.settings.donotShowInfoMsg": true,
    "tslint.autoFixOnSave": true,
    //快速生成标签
    "emmet.triggerExpansionOnTab": true,
    //保存时自动格式化
    "editor.formatOnSave": true,
    "editor.formatOnType": false,
    //自动保存
    "files.autoSave": "afterDelay",
    //延迟3秒自动
    "files.autoSaveDelay": 3000,
    "prettier.tabWidth": 4,
    //"vetur.format.defaultFormatter.html": "prettier",
    //"prettier.semi": false,
    //单引号
    "prettier.singleQuote": true,
    "editor.tabSize": 2,
    "eslint.autoFixOnSave": true,
    "files.associations": {
        "*.vue": "vue"
    },
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        "html",
        {
            "language": "vue",
            "autoFix": true
        }
    ],
    "eslint.options": {
        "plugins": [
            "html"
        ],
        "extensions": [
            ".js",
            ".vue"
        ]
    },
    //排除搜索
    "search.exclude": {
        "**/node_modules": true,
        "**/bower_components": true,
        "**/dist": true
    },
    "explorer.confirmDelete": false,
    "liveServer.settings.donotVerifyTags": true,
    "workbench.startupEditor": "newUntitledFile",
}`
