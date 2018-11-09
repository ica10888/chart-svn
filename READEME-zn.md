# 如何使用

###  安装步骤

1. 将svn文件夹放入 /root/.helm/repository/local
2. `helm install  --name svn  local/svn`
3. 建立相应的 PersistentVolume 

### 使用步骤

1. 第一次使用管理员账号登陆，账号密码：admin/admin ，进入系统后可以修改管理员密码。

2. 添加仓库和用户

3. 使用 TortoiseSVN 就可以访问了。



访问端口

| URL                                    | 用途             | 说明            |
| -------------------------------------- | ---------------- | --------------- |
| http://yourserverip:33343              | HTTP管理员页面   |                 |
| https://yourserverip:34434             | HTTPS管理员页面  |                 |
| http://yourserverip:38080/svn/yourrepo | TortoiseSVN 连接 | SVN checkout... |

