# 说明

使用 vscode debug typescript

## 安装
### node.js
### typescript

## 初始化 typescript 项目,生成配置文件
>tsc

`tsconfig.json`
``` json
{
    "compilerOptions": {
        "module": "commonjs",
        "target": "es5",
        "noImplicitAny": false,
        "sourceMap": false
    }
}
```
### 修改配置
``` json
{
    "compilerOptions": {
        "module": "commonjs",
        "target": "es5",
        "noImplicitAny": false,
        "sourceMap": true,
        "watch":true,
        "outDir": "dist"
    }
}
```

## 添加 index.ts
``` typescript
let title = "world"
let msg = `hello ${title}`
console.log(msg)
```

## 打断点

## F5 开始调试

# 源码 [https://github.com/qwfy5287/typescript-debug-vscode](https://github.com/qwfy5287/typescript-debug-vscode)
