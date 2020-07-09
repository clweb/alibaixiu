# 《阿里百秀》项目说明

### 项目架构

| 系统分层 | 使用技术                                  |
| -------- | ----------------------------------------- |
| 数据层   | mongoDB                                   |
| 服务层   | node.js (express)                         |
| 客户端   | art-template、jQuery、font-awesome、swipe |

### 项目运行环境搭建

1. 安装node.js软件并测试其是否安装成功
   1. win + R 开启windows系统中的运行程序，在运行程序中输入powershell回车，打开命令行程序
   2. 输入`node -v`命令查看node.js的版本，在命令行程序中输出了版本号没有报错即说明安装成功
2. 安装mongodb、mongodb-compass软件
3. 将阿里百秀项目文件夹复制到硬盘中（服务器端程序）
4. 在命令行工具中进入到项目根目录中
   1. 按住shift键，点击鼠标右键，选择在此处打开powershell窗口
5. 使用`npm install`命令安装项目所需依赖文件
6. 将阿里百秀静态页面复制到public文件夹中
7. 在命令行工具中输入node app.js开启项目

