# 关于

这是一个普通的PHP开发环境，包含

- php7.2.19
- composer
- git
- redis5
- es6.7
- mysql5.7
- mongo
- mongo-express


# 如何运行

克隆此项目后执行

1. git clone --recurse-submodules https://github.com/xiaoweiTu/dnper.git
2. 运行
> docker-compose up -d



# 目录分层

config/mysql : 数据库的配置文件

config/nginx : nginx的配置文件

config/php7  : php7的配置文件

config/redis : redis5的配置文件

data/redis : redis数据目录

data/mysql : mysql数据目录

data/mongo : mongodb数据目录

logs/nginx : nginx日志

logs/php   : php日志

www : 项目文件

xhgui-branch: 性能检测平台

# 相关密码

mongo :

ME_CONFIG_BASICAUTH_USERNAME: mongoexpress

ME_CONFIG_BASICAUTH_PASSWORD: mongoexpress

ME_CONFIG_MONGODB_ADMINUSERNAME: mongoadmin 

ME_CONFIG_MONGODB_ADMINPASSWORD: mongoadmin

mysql:

 root:33063306

