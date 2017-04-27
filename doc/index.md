# 说明

用 vscode 调试 typescript

## 安装
### node.js
### typescript
### typescript

## 初始化 typescript 项目
>tsc

```
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
```
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