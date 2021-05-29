1、添加文件（把文件添加进去，实际上就是把文件修改添加到暂存区）： `git add`

2、上传文件（提交更改，实际上就是把暂存区的所有内容提交到当前分支）：`git commit`

3、掌握工作区状态：`git status`

4、查看修改内容：`git diff`

5、版本回退

- `HEAD`指向的版本就是当前版本，因此，Git允许我们在版本的历史之间穿梭，使用命令`git reset --hard commit_id`。
- 穿梭前，用`git log`可以查看提交历史，以便确定要回退到哪个版本。
- 要重返未来，用`git reflog`查看命令历史，以便确定要回到未来的哪个版本。

6、删除文件：`rm <文件名>`，tips：*从来没有被添加到版本库就被删除的文件，是无法恢复的！*

