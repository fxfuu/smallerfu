## [airbnb JavaScript开发规范](https://github.com/airbnb/javascript/tree/es5-deprecated/es5)

## airbnb eslint 配置
### 安装Eslint
```
npm install --g eslint
```
### 安装airbnb
```
npm install --g eslint-config-airbnb
npm install --g eslint-plugin-jsx-a11y
npm install --g eslint-plugin-import
npm install --g eslint-plugin-react
```
### 在当前登录用户的跟目录中创建 .eslintrc.json文件，文件内容为：
```
{
    "extends": "airbnb/legacy",
    "installedESLint": true,
    "plugins": [
        "react"
    ],
    "env": {
        "jquery": true
    }
}
```
### 配置IDEA
1. 打开 Preferences... > Languages & Frameworks > JavaScript > Code Quality Tools > ESlint
2. 勾选“Enable”
3. 选择“Node interpreter”和“ESlint package”路径
4. 选择“Automatic search”