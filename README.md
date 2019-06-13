# 本地局域网建立scratch3.0-gui
## 所需安装软件
- git、node
## 下载源码
` git clone git@github.com:yuanpeng666/scratch3.0_gui.git`

## 进入目录
` cd scratch3.0_gui`
## 依赖库安装
` npm install`
## 启动
` npm start`
- 出现compiled successfully（已成功编译）ok
## PC端访问
- 本地浏览器访问 ` http://127.0.0.1:8601/`或者 ` http://localhost:8601/`进入scratch3.0 GUI
- 成功编译，服务开启，后请勿关闭Git Bash窗口（跑服务中...）
## 手机||平板端访问
- 前提是PC、手机、平板，设备必须处于同一局域网下。
- pc端调出cmd输入 ` ipconfig` 回车，查看找到IPv4地址（比如是192.168.1.110），手机||平板端浏览器访问 ` 192.168.1.110:8601` 即可。