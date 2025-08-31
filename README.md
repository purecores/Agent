For private use only. Unauthorized use or distribution is strictly prohibited.

# 初始化仓库
git init

# 添加所有文件到暂存区
git add .

# 修改分支名称（请将引号中的名称替换为您想要的分支名，例如 master 或 main）
git branch -m ""

# 使用 rebase 策略合并远程仓库 main 分支的代码到本地
git pull --rebase origin main

# 提交 commit 信息（请在引号中填写您的提交信息）
git commit -m ""

# 推送本地 main 分支代码到远程仓库
git push origin main