# lite 在线编程平台
=============================================

### 介绍
    一个轻量级的Scratch在线编程、分享平台

### 功能模块：
1. 注册登录；
2. Scratch创作；
3. 作品管理；
4. 用户管理；
5. 个人信息管理；
6. 作品播放、点赞、收藏、分享。

### 平台构架技术说明：
1. 前端：Layui 框架；
2. 后端：NodeJS + MySQL；

### 开发环境搭建所需要工具（以Windows为例）：
- git：用于下载源代码
- NodeJS：平台运行的服务器（
- MySQL：用户信息、作品保存地
- Python：编译源代码工具之一
- VS Code：源代码开发工具

### 目录说明：

```
lite                            # scratch-cn.lite 目录
├── build                       # Client端文件夹:网页、JS、CSS、IMG
│   ├── css                     #CSS库
│   ├── ejs                     #系统前端文件
│   ├── img                     #IMG库
│   ├── js                      #JS库
│   ├── layui                   #LayUI模块：前端框架
│   ├── scratch                 #scratch编辑器资源文件夹
│ 
├── data                        #所有用户上传的文件
│   ├── material                #scratch作品的素材库
│   ├── scratch_slt             #所有scratch项目的缩略图
│   ├── upload_tmp              #所有上传文件的临时存放目录，该目录正常情况下应该为空，只为临时存放
│   ├── user                    #用户头像文件夹
│
├── node_modules                #整个平台依赖的nodejs模块
├── server                      #Server端文件夹
│   ├── lib                     #Server端共用数据结构库
│   ├── router_admin.js         #系统平台
│   ├── router_my.js            #学习平台
│   ├── router_scratch.js       #scratch模块
│   ├── router_user.js          #用户登录、注册
│
├── app.js                      #平台主程序入口
├── package.json                #平台包依赖文件
├── process.json                #运行nodejs的配置
├── README.md                   #平台说明文件
├── www.comecode.net.sql        #数据库结构文件
```
#### 注：
1. 数据库结构文件中，已包含部分Scratch作品；
2. 数据库结构文件中，已包含平台管理员账号；（账号：comecode，密码：111111)。
