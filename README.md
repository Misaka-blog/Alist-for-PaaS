# Alist for PaaS

TIPS: 可点击仓库的“Use this template”在仓库的原基础上创建私库

![image](https://user-images.githubusercontent.com/122191366/212063458-2def0e1a-805a-4451-ae62-324b67abee47.png)

## 项目特点

* 本项目用于在任意一家 PaaS 云服务商部署 Alist
* 部署完成如发现不能上网，请检查服务是否正常运行

## 部署

* 注册任意一家 PaaS 云服务商
* 根据 PaaS 云服务商的不同绑定自己的 github 账户或使用项目提供的 Actions 生成 DockerHub 镜像，严重建议小号 + 私库
* 项目可用到的变量
  | 变量名 | 是否必须 | 值 | 备注 |
  | ------------- | ------ | ------ | ------ |
  | PORT | 是 | 5244 | Alist 服务端口，一定要5244 |
  | DB_TYPE | 否 | sqlite3，mysql 或者 postgres | 数据库类型 |
  | DB_HOST | 否 | | 数据库地址 |
  | DB_PORT | 否 | | 数据库端口 |
  | DB_NAME | 否 | | 数据库名称 |
  | DB_USER | 否 | | 数据库用户名 |
  | DB_PASS | 否 | | 数据库密码 |
  | DB_TABLE_PREFIX | 否 | | 数据库表前缀 |

* GitHub Actions 用到的变量

  |    变量名     |       备注      |
  | ------------- | -------------- |
  |DOCKER_USERNAME|Docker Hub 用户名|
  |DOCKER_PASSWORD|Docker Hub 密码  |
  |  DOCKER_REPO  |Docker Hub 仓库名|

![image](https://user-images.githubusercontent.com/116990986/211692321-34df154a-320a-448f-9abe-2efab9c53550.png)

## 鸣谢

Alist 项目：https://github.com/hiifeng

## 免责声明

* 本程序仅供学习了解, 非盈利目的，请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权, 如转载须注明来源。
* 使用本程序必循遵守部署免责声明。使用本程序必循遵守部署服务器所在地、所在国家和用户所在国家的法律法规, 程序作者不对使用者任何不当行为负责.

## 赞助

爱发电：https://afdian.net/a/Misaka-blog

![afdian-MisakaNo の 小破站](https://user-images.githubusercontent.com/122191366/211533469-351009fb-9ae8-4601-992a-abbf54665b68.jpg)