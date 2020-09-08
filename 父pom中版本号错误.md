- Maven查看当前生效配置、pom、环境变量等命令（mvn help用法）
https://www.jianshu.com/p/6184fa25fd53
- 打印-X表示打印出debug信息，-Dverbose表示有多少jar被加载可以查看jar包冲突
mvn -X dependency:tree -Dverbose
