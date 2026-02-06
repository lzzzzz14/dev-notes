# 回退 & 高危操作

## 回到上一次提交（保留修改）

git reset --soft HEAD~1

---

## 回到上一次提交（丢弃修改 ⚠️）

git reset --hard HEAD~1

---

## 回到某个 commit（⚠️）

git reset --hard <commit_id>

---

## 只撤销某个文件到指定版本

git checkout <commit_id> -- file

---

## 查看提交历史（简洁）

git log --oneline --graph --all