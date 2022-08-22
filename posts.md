# 这是什么
  这是LazyTong的文档，是一个编程的知识网站，还有一些其他的介绍。
# JavaScript教学
  接下来，就让我们先一起学习JavaScript吧！
## JavaScript简介
JavaScript是一门轻型的浏览器前端脚本语言，在1995年，布兰登·艾奇仅用了十天就完成了这门语言。
### JavaScript的用处
* 表单检验
* 密码强度显示
* 网页特效
* 服务端软件
* 桌面程序
* 手机软件
* 硬件控制
* 网页游戏
### JavaScript的组成部分
* 语法：ECMAScript
* 文档对象模型：Document Object Model
* 浏览器对象模型：Browser Object Model
### JavaScript运行方式
* 通过浏览器运行
#### 渲染引擎
解析HTML和CSS代码，也叫做内核。
#### JavaScript引擎
也叫做JavaScript解释器，可以读取页面的JavaScript脚本代码，编译后运行。
## JavaScript用法
* 实例
表达方式①直接在标签中输入代码
```
<script>alert("test");</script>
```
表达方式②从外部路径中引入
```
<script src=你的JavaScript脚本文件链接></script>
```
* JavaScript引入也许会使用type属性
```
<script type="text/javascript"></script>
```
#### JavaScript可以被引入的地方
* head标签
* body标签
#### 在head标签中使用JavaScript
实例
```
<!DOCTYPE html>
<html>
<head>
<script>
alert("test");
</script>
</head>
<body>
<h1>demo</h1>
<button type="button" onclick="myFunction()">click me</button>
</body>
</html>
```
