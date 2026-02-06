# Dev Notes

个人开发 / 科研常用工具速查合集，目标是 **30 秒内找到需要的命令**。  
顶层 README 提供 **跨工具高频速查 + 清晰导航**，每个工具的完整说明请进入对应目录。

---

## 🚀 快速速查（跨工具 · 高频）

```bash
# Git：查看状态 & 提交
git status
git add .
git commit -m "msg"
git push

# Conda：环境管理
conda env list
conda activate myenv
conda deactivate

# Docker（常用占位）
docker ps
docker images
docker pull images
```

---

## 🧰 工具分区速查

### 🔧 Git（版本控制）

- `git status`
- `git pull`
- `git switch -c dev`
- `git reset --hard HEAD~1` ⚠️

👉 [进入 Git 常用指令](git/README.md)

---

### 🐍 Conda（环境管理）

- `conda create -n myenv python=3.10`
- `conda activate myenv`
- `conda remove -n myenv --all`

👉 [进入 Conda 常用指令](conda/README.md)

---

### 🐳 Docker（容器 · 预留）

- `docker ps`
- `docker images`
- `docker exec -it container bash`

👉 [进入 Docker 常用指令](docker/README.md)

---

## 📁 仓库结构约定

```text
dev-notes/
├── README.md        # 顶层：高频速查 + 导航
├── git/             # Git 专用速查与文档
│   ├── README.md
│   └── docs/
├── conda/           # Conda 专用速查与文档
│   ├── README.md
│   └── docs/
└── docker/          # Docker（预留）
    ├── README.md
    └── docs/
```

### 约定说明

- 顶层 `README.md`
  - 只放 **高频命令 + 工具导航**
  - 不写长解释、不写教程

- 每个工具目录（`git/`、`conda/`、`docker/`）
  - `README.md`：30 秒速查（抄命令）
  - `docs/`：分场景、分问题的详细说明

- 新工具加入时（如 `linux/`、`tmux/`、`ssh/`）
  - 直接按同一结构新增目录
  - 不修改既有结构