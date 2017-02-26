#为348服务的表单

##1. 整体简介
1. 浏览器
2. 服务器（biaodan2）
3. 数据库（mongodb）

##2. 使用说明
step 1：开启mongodb服务器，进入其目录，运行`mongod.exe`

step 2：开启biaodan2，进入其目录，运行`node app.js`

step 3：打开浏览器

##3. 代码说明
####node.js

```
var port = process.env.PORT || 3000  => 定义port的值
app.listen(port)  => 监听，真正起作用监听port端口的代码
console.log('web started on port ' + port)  => 在窗口返回信息
```

