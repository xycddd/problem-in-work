数据库连接长时间没有操作，导致连接失效，所以报出如下异常
```
2020-06-10 13:29:43 [XNIO-2 task-121] [WARN] [com.zaxxer.hikari.pool.PoolBase] [N/A] - HikariPool-2 - 
Failed to validate connection com.mysql.jdbc.JDBC4Connection@375a8ff3 (No operations allowed after connection closed.)
```
解决方法:<br>
https://blog.csdn.net/itguangit/article/details/79178155<br>
https://blog.csdn.net/crystalqy/article/details/90479128
