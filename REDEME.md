# 模块化第三方没有模块化的模块

## 引入(imports-loader)
```
require('imports-loader?$=jquery!./quer.js')
```

## 暴露(exports-loader)
```
require('exports-loader?window.FANGFA!./quer.js')
```