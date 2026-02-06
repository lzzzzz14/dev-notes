# Git / GitHub 常用指令速查

本仓库用于记录 **我自己常用但容易遗忘的 Git / GitHub 操作**，以「我现在要干什么」为索引，而不是系统教程或原理说明。

---

## 🚀 30 秒速查（最常用，直接抄；完整说明见下方各章节）

```bash
# 查看当前状态
git status

# 查看尚未提交的修改
git diff

# 提交所有修改
git add .
git commit -m "msg"
git push

# 拉取远程并合并
git pull

# 新建并切换分支
git switch -c dev
# 旧版本
# git checkout -b dev

# 回退最近一次提交（⚠️ 会丢代码）
git reset --hard HEAD~1
```

---

## 1. 初始化 & 日常提交（最常用）

- 新建仓库
- 关联 GitHub
- 首次 push
- 查看修改
- 提交代码
- 推送到远程  
👉 [docs/01_basic.md](docs/01_basic.md)

---

## 2. 分支操作

- 新建 / 切换分支
- 合并分支
- 删除分支  
👉 [docs/02_branch.md](docs/02_branch.md)

---

## 3. 远程仓库 & 同步

- pull / fetch 区别
- 与远程保持一致  
👉 [docs/03_remote.md](docs/03_remote.md)

---

## 4. 冲突处理（救火）

- merge 冲突
- rebase 冲突
- 放弃本次操作  
👉 [docs/04_conflict.md](docs/04_conflict.md)

---

## 5. 回退 & 高危操作

- 撤销提交
- 回到某个 commit
- 写错 commit 怎么办  
👉 [docs/05_advanced.md](docs/05_advanced.md)