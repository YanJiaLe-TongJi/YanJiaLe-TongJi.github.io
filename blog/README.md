# GitHub Pages Blog

这是一个零依赖的静态个人博客，可以直接通过 GitHub Pages 部署。

## 结构

- `blog/index.html`: 页面内容
- `blog/styles.css`: 样式
- `blog/script.js`: 小型交互脚本
- `.github/workflows/deploy-blog.yml`: 自动部署到 GitHub Pages

## 本地预览

直接双击 `blog/index.html` 即可查看，或者在仓库根目录运行：

```bash
python3 -m http.server 8000
```

然后访问 `http://localhost:8000/blog/`

## 发布到 GitHub Pages

1. 把这个仓库推到 GitHub。
2. 在 GitHub 仓库设置里开启 `Pages`。
3. 选择 `GitHub Actions` 作为部署来源。
4. 之后每次推送到默认分支，博客都会自动发布。

## 自定义

- 把 `Yanjiale` 改成你的名字
- 把 GitHub、Email、LinkedIn 链接替换成你的地址
- 按照现有卡片格式增删文章内容
