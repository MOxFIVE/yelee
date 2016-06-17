# 本地站内搜索


使用搜索需先安装对应插件，用于生成索引数据

> 插件主页: [hexo-generator-search](https://github.com/PaicHyperionDev/hexo-generator-search)

<blockquote class="tip"> <code>#on: true</code> 改为 <code>on: true</code>即为启用搜索</blockquote>

```yaml
search: 
  #on: true
  onload: false
```
`onload: true` : 索引数据 `search.xml` 随页面一起加载 `[效率优先]`

`onload: false` : 当激活搜索框时再下载索引数据 `[按需加载]`

![本地搜索](/src/local-search.gif)
