# 关于

这是一个普通的PHP开发环境，包含
- php7.2.19
- composer
- git
- redis5
- es6.7
- mysql5.7

# 如何运行

克隆此项目后执行

1. 将你的项目文件放在克隆文件夹里的www中
2. 运行
> docker-compose up -d



# 目录分层

config/mysql : 数据库的配置文件
config/nginx : nginx的配置文件
config/php7  : php7的配置文件
config/redis : redis5的配置文件

data/redis : redis数据目录
data/mysql : mysql数据目录

logs/nginx : nginx日志
logs/php   : php日志

www : 项目文件
