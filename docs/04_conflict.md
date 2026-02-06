# 冲突处理

## merge 时出现冲突

git status
# 打开冲突文件，手动修改
git add .
git commit

## 我不想要这次 merge 了

git merge --abort

## rebase 冲突

git rebase --continue
git rebase --abort