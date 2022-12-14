# java环境变量配置

## JAVA_HOME变量设置
- 环境变量 -> 系统变量 -> 新建变量
```
变量名：JAVA_HOME
变量值：jdk安装路径
```

## CLASSPATH变量设置
- 环境变量 -> 系统变量 -> 新建变量
```
变量名：CLASSPATH
变量值：.;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar;
```

## PATH变量设置
- 环境变量 -> 系统变量 -> Path新建两个变量
```
%JAVA_HOME%\bin
%JAVA_HOME%\jre\bin
```