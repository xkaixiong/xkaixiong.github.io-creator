---
title: "如何用hugo搭建博客"
date: 2020-04-30T13:50:47+08:00
draft: false 
---

# hugo搭建博客小教程

1. hugo官网安装hugo，将hugo.exe路径加入PATH，按官网流程配置hugo，step2-step7完成，建立用户名.github.io-creator，配置主题
2. `hugo new posts/博客.md`生成/博客.md，编辑博客内容保存，`draft: false`公开博客内容，`hugo server -D` 本地预览博客内容
3. 别关闭上一个终端，新开终端输入`hugo`创建新目录public,gitignore文件加入/public/让public自成一个仓库
4. ```git init-git add . -git commit -m```输入"文件标题"部署线下仓库
5. github上新建 用户名.github.io仓库，```git remote add origin git@github.com：github用户名/用户名.github.io.git git push -u origin master```将public上传到github
6. 刷新上面的仓库进入settings，github pages选择master branch，点击http://github用户名.github.io查看博客




