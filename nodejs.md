# 下载地址
下载历史版本：https://nodejs.org/en/download/releases/

- 建议不要下载太高版本以免不兼容

12最后一个版本：https://nodejs.org/download/release/v12.22.12/

# 安装
- 点击安装包开始安装
- 修改安装路径
- 一直next
  
# 查看
cmd查看安装版本

- npm -v
- node -v

# 环境配置
- 在nodejs安装路径新增node_global和node_cache文件夹

- cmd输入命令

```
- npm config set prefix "node_global文件夹路径"
- npm config set cache "node_cache文件夹路径"
```

- 环境变量 - 用户变量 - path
```
C:\Users\chenkaihao\AppData\Roaming\npm => node_global文件夹路径
```

- 系统变量 - 新建NODE_PATH 输入node_modules文件路径
- 系统变量 - path - 新增 - %NODE_PATH%

# npm淘宝镜像源
```
npm config set registry https://registry.npm.taobao.org
```
# 下载测试
- 查看node_global/node_modules
```
npm install express -g
```

# 插曲
- 一直下载不报错
- 解决：换成华为镜像源