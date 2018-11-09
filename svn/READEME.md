# README

###  install step

1. put svn folder  into /root/.helm/repository/local
2. `helm install  --name svn  local/svn`
3. careat matched PersistentVolume 

### use step

1. When you login in the administrator platform，the administrator account's username and password is admin/admin .  When you have already logined in ,  you can edit your password .

2. Modify users and repositories .

3. According to use TortoiseSVN , visiting your repositories.

### ports

| URL                                    | purpose                        | explanation            |
| -------------------------------------- | ---------------------------- | --------------- |
| http://yourserverip:33343              | HTTP administrator platform  |                 |
| https://yourserverip:34434             | HTTPS administrator platform |                 |
| http://yourserverip:38080/svn/yourrepo | TortoiseSVN connect          | SVN checkout... |

