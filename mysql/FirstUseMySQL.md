# 啊~是第一次/MySQL的登录与退出
- 作者Cerbur
- 终于安装和搭建完环境了吧
- 迫不及待想做点什么了吧
- 来，让我们第一次和 MySQL ~~交合~~连接  
## 在 CMD 打开 MySQL 的终端
0. 运行你的 wamp 服务
1. Win + R 输入 cmd 打开命令提示符
1. 输入 ``` mysql -uroot -p[password]``` 然后enter  
这里 ```-u``` user的缩写后面紧贴你的用户名  
开始自带一个有着所有权限的用户root  
以后你可以自己创建新的用户  
```-p``` password的缩写后紧贴刚刚你输的密码  
![Alt text](https://github.com/CerteKim/BNG/blob/master/mysql/img/mysqlloginwithpwd.png)   
```警告：这样子登录会明文暴露密码，不推荐使用```  
```所以另一种登录方式是 mysql -uroot -p```  
```enter 后再输入非明文密码这样更安全```  
![Alt text](https://github.com/CerteKim/BNG/blob/master/mysql/img/mysqlloginnopwd.png)    
1. 输入完密码 enter 后就进入了 MySQL 的欢迎界面  
![Alt text](https://github.com/CerteKim/BNG/blob/master/mysql/img/mysqlhomepage.png)    
1.输入 ```exit``` 即可退出 MySQL    
![Alt text](https://github.com/CerteKim/BNG/blob/master/mysql/img/mysqlbye.png)    
- 好哒现在已经完成了 MySQL 的登录与退出了  
- 熟悉一哈这些步骤  
- 接下来我们就开始要和数据库打交道啦  
