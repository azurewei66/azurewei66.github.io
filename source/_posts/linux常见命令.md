---
title: linux常见命令
date: 2022-05-03 14:10:12
tags:
---

# Linux常见命令

## 用户管理

```java
//新建用户
useradd 选项 用户名
    选项:
-c comment 指定一段注释性描述。
-d 目录 指定用户主目录，如果此目录不存在，则同时使用-m选项，可以创建主目录。
-s Shell文件 指定用户的登录Shell。
-u 用户号 指定用户的用户号，如果同时有-o选项，则可以重复使用其他用户的标识号。
用户名:指定新账号的登录名
Example:
useradd –d  /home/sekiro -s /bin/sh -m sekiro
    新建sekiro用户，用户目录在/home/sekiro,登录方式为 sh
//修改密码
    passwd
    
 //删除用户
    userdel
    
 //修改帐号
    usermode
   
```



