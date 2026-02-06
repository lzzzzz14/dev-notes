# 远程仓库 & 同步

## 查看远程仓库

git remote -v

---

## 拉取远程更新（不合并）

git fetch origin

---

## 拉取并合并（最常用）

git pull

---

## 本地分支落后远程，强制对齐（⚠️ 会丢本地修改）

git fetch origin
git reset --hard origin/main

---

## 推送当前分支

git push