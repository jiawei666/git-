## 7.25
* 本地分支命令
>创建本地分支并切换到此分支并指定远端分支:`git checkout -b <branchName> <remoteName>`<br>
>以上几个步骤可以拆开来做：<br>`git branch <branchName>`//创建分支<br>
>`git checkout <branchName>`//切换分支<br>
>`git branch --set-upstream-to origin/<remoteName> <branchName>`//指定远端分支<br>

* 远端分支创建
>因为远端分支创建是通过push时实现的，所以:<br>
>`git push origin <remoteName>` 或者 `git push origin <branchName>:<remoteName>` // `<remoteName>`必须与当前提交分支的名字一样<br>
>`git push origin :<remoteName>` // 删除远端分支
