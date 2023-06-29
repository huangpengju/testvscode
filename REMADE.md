# 这里是REMADE.md文件
这个项目用于练习使用ssh链接项目，并使用VSCode上传代码，参考博客：https://blog.csdn.net/m0_51185558/article/details/126181439
## 收获
1. 把在本地电脑生成的ssh key秘钥文件(.ssh文件夹内)，添加到github上 SSH and GPG keys (New SSH key)
2. 在VSCode终端输入  ssh -T git@github.com
3. 在github中新建一个项目，如testvscode,赋值ssh
4. 在使用VSCode打开的本地项目终端中，输入git remote add origin 上一步复制的ssh，与github建立联系
5. 初始化仓库git init，默认分支是master
6. 把本地项目中的文件，添加到暂存区
7. 填写注释信息，点击提交到本地分支
8. 拉取（拉取自...），推送（推送到...）


