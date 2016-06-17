# 404 页面

使用 Hexo 命令新建一个名为 `404` 的页面 

```
hexo new page 404
```

`/source/404/index.md` 文件中添加  `permalink: /404` 

```yaml
title: 404 Not Found：该页无法显示
toc: false
comments: false
permalink: /404
---
```

<blockquote class="tip">
    404 页面显示效果可以在本地查看 <code>http://localhost:4000/404.html</code>
</blockquote>

<blockquote class="note">
    无效网址自动跳转 404 页面则必须在线上测试
</blockquote>

## 样式参考
<blockquote class='example'>
    <a href="http://moxfive.xyz/2015/10/16/hexo-404-page/" target="_blank">在 Hexo 中创建匹配主题的404页面</a>
</blockquote>

![404 Page](/src/404-page.png)
