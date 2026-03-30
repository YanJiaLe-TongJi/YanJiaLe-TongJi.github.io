# 个人主页维护说明

线上地址：

- https://yanjiale-tongji.github.io/

## 改哪里

- 页面内容：`index.html`
- 页面样式：`styles.css`
- 小脚本：`script.js`
- 后续文章原稿：你可以直接给我 `.md` 或 `.docx`

GitHub Pages 当前直接发布仓库 `main` 分支根目录，所以以后只维护根目录这一套文件即可。

## 怎么发布

在仓库根目录执行：

```bash
git add index.html styles.css script.js README.md
git commit -m "更新主页"
git push
```

推送到 `main` 后，GitHub Pages 会自动重新发布。

## 写文章的方式

- 你可以直接写 Markdown
- 也可以直接写 Word 文档
- 你把文件给我后，我来帮你整理成网页内容并推送上线

如果是 Word，我会先提取正文和标题，再按主页风格排版。
如果是 Markdown，我会尽量保留原有结构后再发布。

## Codex Skill

本地已经添加了一个 skill：

- `~/.codex/skills/update-blog`

重启 Codex 后即可触发。常见说法：

- “用 update-blog skill 更新主页文案”
- “用 update-blog skill 新增一条最近更新”
- “用 update-blog skill 调整主页样式并发布”
- “用 update-blog skill 把这篇 md 文章发到博客”
- “用 update-blog skill 把这篇 Word 文档整理后发布”
