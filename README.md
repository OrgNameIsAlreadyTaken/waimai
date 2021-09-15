# waimai

# 重来吧

/remake


# 初始化流程:
文件夹中打开vscode
终端内:git init
          git remote add   你自定义的l连接时用的英文名字   GitHub代码
          git pull   你自定义的l连接时用的英文名字  main
          
          cd waimai
          npm i
初始化结束

# 提交流程:
终端内:
git add .  //暂存所有更改
git commit -am "提交时的说明"  //把已经暂存的文件提交
git push 你的本地分支 :main  //本地分支用 git branch 查询 ,"提交时的说明" 会在成功推送后显示在仓库内,建议每次提交时交代本次推送的改动

# 特别提示
在每次开始码字前和提交前,务必先pull一遍,
以便处理文件冲突

# 常用git命令
https://blog.csdn.net/halaoda/article/details/78661334