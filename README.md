# 模块化第三方没有模块化的模块

## 引入(imports-loader)
```
require('imports-loader?$=jquery!./quer.js')
```

## 暴露(exports-loader)
```
require('exports-loader?window.FANGFA!./quer.js')
```
### 使用
```
yarn serve

使用浏览器打开inde.html文件即可
```

