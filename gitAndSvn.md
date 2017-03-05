# git 有关总结

1.对相关文件夹内进行鼠标右键git bash here操作。
2.使用git必须先对需要管理的相关文件所在文件夹进行 git init
3.对相关文件进行git add 文件名操作，添加进仓库。
4.再进行git commit操作，将文件提交到仓库。

完成以上三步之后，将文件推送的远程仓库。有以下步骤
1.在github上建立一个仓库，仓库名为英文。
2.建立好仓库后，我们可以得到一个仓库地址，例：
`https://github.com/WenAce/summarize.git`
3.我们通过git进行推送文件至远程仓库操作。
`git remote add origin https://github.com/WenAce/summarize.git`
4.最后进行git push -u origin master操作。

下面为一些git常用命令
> git status 查看仓库当前状态，当我们看到文件为红色字体，说明这个文件还未添加到仓库
  绿色则代表已经添加成功。
  git diff 查看已经修改内容
  git commit -m (-m后输入你提交的相关说明，将出现在此文件旁进行标识)
  git log 查看最近提交日志。


# SVN 总结

svn和git大体相同
1.首先我们需要客户端的svn和服务器的svn，分别为[TortoiseSVN](https://tortoisesvn.net/downloads.html)
和[VisualSVN](https://www.visualsvn.com/server/download/)
2.然后分别安装。因为可视化的原因，svn相对于git来说操作更加简单点。
