# 文章摘要

目前主题可使用两种方式在首页显示文章摘要而不是全文。

### 方法一: `<!-- more -->`

``` diff
title: Hello World
date: 2015-12-03 00:00:00
---
<Excerpt in index | 首页摘要> 
+<!-- more -->
<The rest of contents | 余下全文>
```

<blockquote class="note">
    <code>&lt;!-- more --&gt;</code> 之前最好不要有空格等字符；
</blockquote>

### 方法二: `description` in [Front-matter](https://hexo.io/zh-cn/docs/front-matter.html)

``` diff
title: Hello World
date: 2015-12-03 00:00:00
+description: "Welcome to Hexo! This is your very first post."
---
<Contents>
```

<blockquote class="note">
    通过 <code>description</code> 添加的摘要只能为纯文本；
</blockquote>

<blockquote class="tip">
    <code>description</code> 中的内容加引号，可以避免一些程序错误，例如当内容里包含英文冒号时。
</blockquote>


---
![文章摘要](/src/post-excerpt.png)
