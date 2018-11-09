# README

###  install step

1. put svn folder  into /root/.helm/repository/local
2. `helm install  --name svn  local/svn`
3. careat matched PersistentVolume 

### use step

1. when you login in the administrator platform，the administrator account's username and password is admin/admin .  when you has already logined in ,  you can edit your password .

2. Modify users and repositories .

3. According to use TortoiseSVN , visit your repositories.

### ports

| URL                                    | 用途                         | 说明            |
| -------------------------------------- | ---------------------------- | --------------- |
| http://yourserverip:33343              | HTTP administrator platform  |                 |
| https://yourserverip:34434             | HTTPS administrator platform |                 |
| http://yourserverip:38080/svn/yourrepo | TortoiseSVN connect          | SVN checkout... |

