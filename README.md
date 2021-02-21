# ejabberd-docker

ejabberd docker-compose

提前建立upload 和sqlite文件夹，并设置所有者chown 9000:9000 否则无法建立数据库


新建管理员账户
`docker-compose exec  ejabberd bin/ejabberdctl register admin myejabberd.com passw0rd`
