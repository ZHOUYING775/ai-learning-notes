# AI 学习知识库

这是一个用 Markdown + Git 管理的 AI 学习笔记库。

## 你可以怎么使用

1. 先阅读 `00-开始这里/学习路线.md`。
2. 学到一个概念，就复制 `99-模板/知识卡片模板.md`，改成合适的文件名。
3. 把笔记放进对应目录，例如提示词放到 `02-提示词工程/`。
4. 每完成一小块内容就保存一次 Git 版本。

## 推荐的学习节奏

- 每天：记录 1 个概念、1 个例子、1 个疑问。
- 每周：整理一次目录，删除重复内容，补充自己的总结。
- 每月：做一个小项目，并在 `06-项目实践/` 记录过程和结果。

## Git 最常用的 4 个命令

在本文件夹打开终端后执行：

```bash
git status              # 查看哪些文件发生了变化
git add .               # 把变化放进本次版本
git commit -m "记录本周学习"  # 保存一个版本
git log --oneline       # 查看历史版本
```

## 推送到 GitHub 或 Gitee

先在网站上创建一个空仓库，然后在本地执行（把地址换成你自己的）：

```bash
git branch -M main
git remote add origin https://github.com/你的用户名/ai-learning-notes.git
git push -u origin main
```

以后每次同步只需要：

```bash
git add .
git commit -m "补充 RAG 笔记"
git push
```

## 注意事项

- 不要把 API Key、密码、个人隐私放进笔记；`.gitignore` 已经忽略常见的 `.env` 文件。
- 先写自己的理解，再附上官方链接；不要只复制粘贴资料。
- 文件名尽量清楚，例如 `什么是向量数据库.md`。
