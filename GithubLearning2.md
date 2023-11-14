# **方法一**
## 第一步：邀请
userA创建一个repository，将想共同完成的项目上传，然后在当前repository中的setting中选择Collaborators，search userB向他发送合作邀请
## 第二步：uesrB修改代码
user B将需要共同完成的项目用git clone到本地，在git bash中输入git clone https://githubfast.com/userAname/repository_name  D:/clone_file即可clone完成，然后userB在本地修改项目内容
## 第三步：userB上传修改内容
右键项目文件所在文件夹，打开git bash，输入git add .和git commit -m "说明"，然后输入git push，就可以把修改上传到服务器，userA就可以看到其Github上的项目更新了

# 方法二：fork仓库同步
这个方法userA 和userB 使用不同的repository， 代码安全性高，但是管理好复杂。
## 第一步fork代码clone到本地
userA 新建了repository，上传了项目，邀请了userB以后，userB接受邀请以后，可以在GitHub上点击fork 把项目复刻到自己的repository中。然后在git bash中把项目clone到本地
## 第二步：修改并上传
user B将需要共同完成的项目用git clone到本地，在git bash中输入git clone https://githubfast.com/userAname/repository_name  D:/clone_file即可clone完成，然后userB在本地修改项目内容右键项目文件所在文件夹，打开git bash，输入git add .和git commit -m "说明"，输入git cofing --global --edit,然后在显示的内容的最后输入
然后输入git push，就可以把修改上传到服务器，userA就可以看到其Github上的项目更新了
