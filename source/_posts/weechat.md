title: 在Termux里聊天
date: 2017-05-01
categories: Termux
tags: Termux
---

在termux里聊天需要用到weechat.  
安装weechat  
`apt install weechat`  
输入`weechat`进入.  
输入`/help`查看使用方法.  
这里提供一些简单操作.    

<!-- more -->
添加服务器.  
`/server add freenode irc.freenode.net`   
连接服务器.   
`/connect freenode`    
注册帐号. (不注册也可以聊)   
`/msg NickServ REGISTER 名称 密码 邮箱`   
输入时，如果上面名称变成*号说明是以当前默认用户名注册，改成。  
`/msg NickServ REGISTER 密码 邮箱`    
改名.  
`/nick 新名字`    
进入频道.  (频道一般以#开头)  
`/join #funs`    
和别人开小窗单独聊天.   
`/query 昵称|#频道`   
离开频道.  
`/part`   
退出服务器.   
`/quit`   
#### 更多相关命令请百度或谷歌
