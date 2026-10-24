---
title: "Hello World · 博客开张"
date: 2026-10-23
---
这是博客的第一篇文章 / This is the first post.

## 怎么写新文章 / How to write a post

在 `_posts/` 目录下新建一个 Markdown 文件，**文件名必须是 `年-月-日-标题.md` 格式**：

```text
_posts/
└── 2026-10-23-hello-world.md   ← 这篇
└── 2026-10-25-my-next-post.md  ← 下一篇
```

文件开头加上 front matter（两行 `---` 之间）：

```yaml
---
title: "文章标题"
date: 2026-10-25
---
```

然后 `git push` 推送到 GitHub，一两分钟后文章就会自动出现在 [博客列表](/blog/) 和首页，无需任何手动构建。

## Markdown 语法都支持 / Markdown works

写**粗体**、*斜体*、[链接](https://github.com/k4son)、列表：

- 中文写作没问题
- English works too
- 代码块也支持

```python
def hello():
    print("Hello from k4son.github.io!")
```

> 引用块：最好的学习方式是动手构建。
> The best way to learn is to build.

删掉这篇文章随时可以，直接删除文件再 push 即可。
Delete this post anytime by removing the file and pushing.
