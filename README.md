# 激活环境
source ll_env/bin/activate

# 建立环境
python3 -m venv ll_env

# 服务
python3 manage.py runserver

# 创建应用程序
python3 manage.py startapp learning_logs


python3 manage.py makemigrations learning_logs



修改models.py;对learning_logs 调用makemigrations ;让Django迁移项目。


# 创建用户
python3 manage.py createsuperuser