## 项目介绍

数据库管理系统

### 项目名
app-zebra-admin

### 开发指南

```bash
# 克隆项目
git clone git@git.intra.im:frontend/app-zebra-admin.git
cd app-zebra-admin

# 配置作者
git config user.name "你的昵称"
git config user.email "你的邮箱"

# 安装依赖
npm config set @lingshou:registry http://r.npm.intra.im
npm install

# 本地构建
npm run build

# 本地起服务
npm run dev

# 本地访问
http://localhost:8080/dist/

```

### 项目地址

[数据库管理系统beta环境](http://zm-beta.intra.im/)

账号：oss登录账号
密码：oss登录密码

[数据库管理系统product环境](http://oss.owitho.com)

账号：找 `@高得顺` 申请权限

### 使用技术

技术栈：vue + vue-router + axios + es6/7 + less

工具：webpack


## 项目结构

``` html
.
├── .babelrc            #babel的配置文件
├── .gitignore          #git ignore文件
├── README.md           #项目说明文档
├── build               #构建脚本目录
├── package.json
├── src                 #业务目录
│   ├── assets          #静态资源
│   ├── api             #接口请求
│   ├── router          #路由配置
│   ├── lib             #公共库
│   ├── components      #公共组件
│   ├── modules         #业务模块
│   ├── views           #业务入口
│   └── index.js        #入口文件
├── template            #html模版目录，用于webpack html plugin
│   └── index.ejs
└── webpack.config.js   #webpack配置文件
```
