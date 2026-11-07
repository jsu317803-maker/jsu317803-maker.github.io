---
layout: post
title: "你好，世界：博客上线了"
date: 2026-11-07 16:00:00 +0800
categories: [随笔]
tags: [Jekyll, GitHub Pages, 建站]
---

这是博客的第一篇文章，用来演示 Markdown 的写法。熟悉之后可以直接删掉这个文件，换成你自己的内容。

## 写新文章只需三步

1. 在 `_posts/` 里新建文件，文件名格式必须是 `YYYY-MM-DD-title.md`，例如 `2026-11-08-my-second-post.md`。
2. 在开头写 YAML front matter，指定 `title`、`date`、`categories`、`tags`。
3. 提交并推送，GitHub Pages 会自动构建发布。

```bash
git add _posts/2026-11-08-my-second-post.md
git commit -m "post: 第二篇文章"
git push
```

## 常用的 Markdown 语法

正文支持 **加粗**、*斜体*、[链接](https://jekyllrb.com/)、行内代码，以及列表：

- 无序列表项一
- 无序列表项二

> 引用块可以用来划重点，或者摘录一段话。

代码块带语法高亮（Rouge），语言标识要小写：

```yaml
title: 文章标题
date: 2026-11-07 16:00:00 +0800
tags: [Jekyll, GitHub Pages]
```

| 语法 | 效果 |
| --- | --- |
| `**文字**` | 加粗 |
| `` `代码` `` | 行内代码 |
| `> 引用` | 引用块 |

## 几个小提醒

- 文章日期写在未来默认不会发布（本地预览加 `--unpublished --future` 可强制显示）。
- 图片放进 `assets/` 或任意普通目录，用 `![说明](/assets/xxx.png)` 引用；项目站点请改用 `relative_url`。
- `<!--more-->` 不算摘要分隔符，想控制首页摘要可用 `excerpt_separator` 或在 front matter 里写 `excerpt`。

祝写得开心。
