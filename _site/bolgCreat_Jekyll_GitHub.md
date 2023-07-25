# Jekyll + GitHub

[toc]
<!-- 后续改 -->

[Jekyll + Github Pages 搭建个人免费博客](https://zhuanlan.zhihu.com/p/87225594)

<div STYLE="page-break-after: always;"></div>

# 配置步骤
## 1、安装Ruby
Ruby，一种简单快捷的面向对象（面向对象程序设计）脚本语言
本地安装的版本是 ruby 3.0.4p208 (2022-04-12 revision 3fa771dded) [x64-mingw32]
同过CMD查看版本信息 ruby -v

## 2、安装RubyGems
RubyGems是Ruby的一个包管理器
解压下载的安装包 [RubyGems](https://rubygems.org/pages/download)
```
cd D:\rubygems-3.0.6	          #切换文件目录 
ruby setup.rb                     #安装
gem -v                            #查看rubygems版本号
```

## 3、安装Jekyll
Jekyll • 简单静态博客网站生成器
通过RubyGems安装
```
gem install jekyll               #安装jekyll  
jekyll -v                        #查看jekyll版本号
```

## 4、创建本地项目
本地项目只能通过本地打开
```
jekyll new restlessManBlog     #新建博客 
cd restlessManBlog             #切换目录 
jekyll server                  #启动服务器
```

## 5、启动服务器
打开浏览器访问：http://localhost:4000/

## 5、添加 MarkDown 文档
在项目根目录下的 _posts 目录创建 markdown 文档。这里注意 md 文档命名要添加 “yyyy-mm-dd”的前缀。
例如：2019-10-11-5分钟搭建博客.md

## 7、创建GitHub账号
## 8、创建代码仓库
## 9、部署代码到Github
在我们创建的博客的目录中找到 _site 目录，将 _site 目录下的所有文件都提交到Github上。
我这里是上传了bolg所有工程。



# 配置过程中遇到的问题




