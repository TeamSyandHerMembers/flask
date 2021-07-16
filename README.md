# Flask

## 一、后端内容

----
## 目录
* [简介](#jump1)
* [安装](#jump2)
* [项目布局](#jump3)
* [操作步骤](#jump4)
----
## <span id="jump1">1. 简介</span>
创建一个名字为“Flaskr”的基本博客应用程序。用户将能够注册、登录、创建帖子，
也能编辑或删除自己的帖子。

视图如下：
1、注册
![web1 图标](https://github.com/webtestings/Flask-exercise/blob/main/web1.png)

2、登录
![web1 图标](https://github.com/webtestings/Flask-exercise/blob/main/web1.png)

3、注销
![web1 图标](https://github.com/webtestings/Flask-exercise/blob/main/web1.png)

## <span id="jump2">2. 安装</span>
配置Python虚拟环境  

`. venv/bin/activate`   

`python3 -m venv venv`

安装flask
`pip install flask`

## <span id="jump3">3. 项目布局</span>
创建项目目录输入：
```python
$ mkdir flask-tutorial
$ cd flask-tutorial
```
项目目录将包含：**flaskr/**、**tests/**、**venv/**。
* flaskr/包含应用程序代码和Python源代码文件。
* tests/包含测试模块的目录。
* venv/包含Python虚拟环境和密钥。

## <span id="jump4">4. 操作步骤</span>
1、进入gitpod
2、输入下列操作命令
```python
pip install flask
export FLASK_APP=flaskr
export FLASK_ENV=development
flask init-db
pip install waitress
waitress-serve --call 'flaskr:create_app'
```
