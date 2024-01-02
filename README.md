运行方式：

1 IntelliJ IDEA Run/Debug Configurations

  菜单路径：Run>Edit Configurations
  
    在弹出界面配置增加一个Maven配置项。
    
    Name输入：MybatisConfigGenerator
    
    Run输入： mybatis-generator:generate -e
    
    Working directory： 选择当前项目即可
    

2 直接用mvn命令执行

   mvn mybatis-generator:generate -e
