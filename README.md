## 申明：本项目为学习使用，非原创。
原项目地址： 
git clone https://github.com/k3oni/pydash.git

### 使用virtualenv运行本项目：
```
1.创建运行环境：
    virtualenv -p /usr/local/bin/python2.7.9 pydash

2.激活环境：
    source bin/activate

3.下载项目：
    git clone https://github.com/k3oni/pydash.git

4.安装项目所需包：
    pip install -r requirements.txt

5.创建认证表：
    python manage.py syncdb

6.启动项目：
    nohup python manage.py runserver 0.0.0.0:1234 &

7.退出环境：
    deactivate
```
