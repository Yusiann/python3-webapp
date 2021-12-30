# 搭建开发环境

1、下载Python3，并安装第三方库，我用的是Anaconda。建议边做边连接GitHub同步。

确认安装版本

```
$python3 --version 
```

异步框架aiohttp

```
$pip3 install aiohttp
```

前端模板引擎jinja2

```
$pip3 install jinja2
```

Mysql的Python异步驱动程序aiomysql

```
$pip3 install aiomysql
```

2、下载Mysql数据库，官网下载，牢记root口令

3、建立目录

```
awesome-python3-webapp/  <-- 根目录
|
+- backup/               <-- 备份目录
|
+- conf/                 <-- 配置文件
|
+- dist/                 <-- 打包目录
|
+- www/                  <-- Web目录，存放.py文件
|  |
|  +- static/            <-- 存放静态文件
|  |
|  +- templates/         <-- 存放模板文件
|
+- ios/                  <-- 存放iOS App工程
|
+- LICENSE               <-- 代码LICENSE
```

5、开发工具

我用的VScode，先mark一下，后期出问题再改。