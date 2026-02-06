# 冲突处理

## merge 时发生冲突

git status
# 手动打开冲突文件，修改后：
git add .
git commit

---

## 放弃这次 merge

git merge --abort

---

## rebase 冲突

git status
# 修改冲突文件
git add .
git rebase --continue

---

## 放弃 rebase

git rebase --abort