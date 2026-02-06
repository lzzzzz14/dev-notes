# 分支操作

## 查看所有分支

git branch
git branch -a

---

## 新建并切换分支

git checkout -b dev
# 或（新版本）
git switch -c dev

---

## 切换分支

git checkout main
# 或
git switch main

---

## 合并分支到当前分支

git merge dev

---

## 删除分支

git branch -d dev        # 已合并
git branch -D dev        # 强制删除