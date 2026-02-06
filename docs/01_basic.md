# 基础 & 日常使用

## 初始化一个仓库

git init
git add .
git commit -m "init"
git branch -M main
git remote add origin git@github.com:USER/REPO.git
git push -u origin main

---

## 查看当前状态（最常用）

git status

---

## 查看修改内容

git diff          # 尚未 add 的改动
git diff --cached # 已 add 但未 commit 的改动

---

## 提交所有修改（标准流程）

git add .
git commit -m "xxx"
git push

---

## 只提交部分文件

git add file1 file2
git commit -m "xxx"

---

## 提交信息写错了（还没 push）

git commit --amend