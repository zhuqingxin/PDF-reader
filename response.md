login.java
return Value
1:401
2:404
3:400
4:403
5:



TYPE
---------------------------------------
值            |          意义         |
--------------|-----------------------|
 1            |   注册                |
--------------|-----------------------|
 2            |   上传文件            |
--------------|-----------------------|
3             |      登录             |
--------------|-----------------------|
4             |   请求获取个人文件    |
--------------|-----------------------|
5             |   请求获取所有文件    |
--------------|-----------------------|
6             |     下载文件          |
---------------------------------------



result
---------------------------------
值          |  意义             |
--------------------------------|
100         | 成功              |
--------------------------------|
200         | 失败              |
---------------------------------


resason
----------------------------------
值          | 意义                |
------------|---------------------|
400         | 成功                |
------------|---------------------|
401         | 连接数据库失败      |
------------|---------------------|
402         | 账号密码错误        |
------------|---------------------|
403         | 账号已存在          |
------------|---------------------|
404         |sql语句错误          |
------------|---------------------|
405         | ResultSet错误       |
------------|---------------------|--
406         | 上传文件失败        |
------------|---------------------|--
407         |  账号不存在         |
------------|---------------------|----
408         | 获取表单失败        |
------------|---------------------|--  
409         | 添加内容到返回值失败|
------------|---------------------|---
410         | 数据库事务回退失败  |
----------------------------------|--
411         | 数据库事务提交失败  |
------------|---------------------|---
412         | 下载文件失败        |
-----------------------------------