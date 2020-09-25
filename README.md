# ToolsShell
- mysql

- gitlab

  

```shell
vim /home/gitlab/config/gitlab.rb
# 配置http协议所使用的访问地址,不加端口号默认为80
external_url 'http://192.168.0.103'
gitlab_rails['gitlab_ssh_host'] = '192.168.0.103'
gitlab_rails['gitlab_ssh_user'] = '222'

```

- cloud9
> 在线编辑IDE

- gitignore.io
> 快速生成 gitignore文件
>
> 这个启动了只能本地可以用，做了一个nginx代理

- nginx
- portainer

> docker 监控工具