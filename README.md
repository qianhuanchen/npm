# npm
npm的一些使用方法
# 使用nrm
nrm是一个npm源管理器，可以在各种npm源之间切换  
### 安装nrm 
```
npm install -g nrm
```
### 查看可选源 
```
nrm ls
```
### 测试速度
看哪个快就切换哪个
```
nrm test
```
### 切换源
```
nrm use {taobao}
```
# 使用nodemon
nodemon工具可以让你修改了代码之后自动重启node服务(默认启动index.js文件)
### 安装
```
npm install -g nodemon
```
### 启动服务
```
nodemon app.js
```
