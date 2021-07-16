# Flask

## 一、后端内容

----
## 目录
* [简介](#jump1)
* [界面](#jump2)
* [安装](#jump3)
* [操作步骤](#jump4)
----
## <span id="jump1">1. 简介</span>
创建一个名字为“Flaskr”的基本博客应用程序，并使用Bootstrap改进Flaskr的UI。
用户将能够注册、登录、创建帖子，也能编辑或删除自己的帖子。

## <span id="jump2">2. 界面</span>
改进前

创建帖子
![photo1 图标](https://github.com/justina0/flask/blob/main/flaskr/static/images/photo1.png)

改进后

首页
![photo2 图标](https://github.com/justina0/flask/blob/main/flaskr/static/images/photo2.png)

登录
![photo3 图标](https://github.com/justina0/flask/blob/main/flaskr/static/images/photo3.png)

注册
![photo3 图标](https://github.com/justina0/flask/blob/main/flaskr/static/images/photo4.png)

创建帖子
![photo5 图标](https://github.com/justina0/flask/blob/main/flaskr/static/images/photo5.png)

## <span id="jump3">3. 安装</span>
配置Python虚拟环境  

`. venv/bin/activate`   

`python3 -m venv venv`

安装flask
`pip install flask`

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


