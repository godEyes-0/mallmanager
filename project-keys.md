vue init webpack 项目名称  创建
#### 01-项目-准备项目目录说明
1.src/
2.build/ webpack相关代码
3.config/ 本地服务器配置
4. .eslintignore eslist排除文件
5. .eslinttrc eslint配置文件

#### 02-项目-准备-代码规范-自定义指令-lintfix
1.结尾没有分号（；）
2，必须用全等
3.不允许出现未使用的变量
4.不允许出现一个以上空行

> 在package.json中scripts自定义指令：指令很长
> npm run 自定义指令名(dev)
> npm run lintfix(自动按照规范修正全部(但是，多余的变量这个error不会修正)的js代码)
"lintfix": "eslint --ext .js,.vue src --fix",

> 自动打开浏览器dev：'xxxxxxx --open'

> 关闭eslint build/webpack.base.conf.js注释掉

#### 03-项目-准备-element-ui文档分析
> element-ui 是饿了么开发团队
> 适用于vue项目-PC端项目
> 在main.js引入

#### 04-项目-准备-element-ui-安装-引入
> npm i element-ui -S
> 在main.js import
> Vue.use(ElementUI)

#### 05-项目-准备-项目模块简化-调整
> 删除模板中我们用不到的文件/代码

#### 06-项目-准备-git版本控制
> git/svn
1.git init -> .git  (在当前目录新建一个Git代码库)
2.git status  (显示有变更的文件)
3.git add .  (添加当前目录的所有文件到暂存区)
4.git commit -m "注释"
5.在代码托管平台(github)新建远程仓库
6.git branch -M main
  git remote add origin https://github.com/yuankai5510/mallmanager.git
  git push -u origin main

#### 07-项目-登录-新建分支-login组件-配置路由
> 新建一个分支 专门写登录功能
>git branch (列出所有本地分支)
>git checkout -b 分支名 (git checkout -b dev-login)
> 新建组件+配置路由
> 注意：
1.commit没完成一个小功能就commit一次
2.push操作master去完成
#### 08-项目-登录0引入表单组件
#### 08-项目-登录-样式调整
#### 01-项目-准备项目目录说明
#### 01-项目-准备项目目录说明
