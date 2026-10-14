# git-1

Git 练习与版本控制实验仓库。

## 这个仓库用来做什么

- 练习 Git 基本操作：`add` / `commit` / `branch` / `merge` / `rebase`
- 记录学习过程中的代码和笔记
- 验证远程仓库工作流：`push` / `pull` / `fetch`

## 常用命令速查

```bash
# 查看当前状态
git status

# 暂存并提交
git add .
git commit -m "feat: 描述这次改了什么"

# 查看历史（简洁一行版）
git log --oneline --graph --all

# 推送到远程
git push

# 拉取远程更新
git pull --rebase
```

## 提交信息规范（建议）

| 前缀 | 含义 |
|---|---|
| `feat:` | 新增功能 |
| `fix:` | 修复问题 |
| `docs:` | 只改文档 |
| `refactor:` | 重构，行为不变 |
| `test:` | 增删测试 |
| `chore:` | 杂项（配置、依赖） |

## 备注

第一次提交由初始化脚本自动创建，可以直接修改本文件内容后提交，用来练习完整流程。
