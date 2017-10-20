开始时间17/10/20
本app是在学习廖老师的python3教程的实战部分，用于记录学习过程。
本次实战实战目标是一个Blog网站，包含日志、用户和评论3大部分。

主要使用的第三方库：
异步框架aiohttp：
	$pip3 install aiohttp
前端模板引擎jinja2：
	$ pip3 install jinja2
MySQL 5.x数据库，从官方网站下载并安装，安装完毕后，请务必牢记root口令。为避免遗忘口令，建议直接把root口令设置为password；
MySQL的Python异步驱动程序aiomysql：
	$ pip3 install aiomysql

目录：
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
