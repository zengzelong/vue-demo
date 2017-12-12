# vue-demo
> vue 基础范例  


## 构建测试环境

1. 初始化项目
```
> npm init -y
```
2. 添加 browser-sync
```
> npm install --save-dev browser-sync
```

3. 编辑启动脚本
```
vi package.json
```
```
"scripts": {
  "test": "echo \"Error: no test specified\" && exit 1",
  "start": "./node_modules/.bin/browser-sync start --server --no-notify --files='*.html, *.css, *.js'"
}
```

4. 启动测试
```
> npm run start
```
