# 评论设置

主题目前支持 Disqus，多说 及 友言评论，把 `#on: true` 改为 `on: true` 即启用对应评论系统

<blockquote class="note"> 选 <b>一个</b> 作为网站评论系统，其他保持 <b>禁用</b> <code>#on: true</code></blockquote>

## 动态加载评论模块
![动态加载评论](/src/load-comment.gif)
```yaml
preload_comment: true
## true: 评论区跟随页面一起加载
## false: 当点击评论条等区域时再加载评论模块
```

## 评论数显示
选择是否在主页文章标题旁显示评论数（支持 多说 和 Disqus）

```
show_count: false
```

## 1. Disqus
![Disqus](/src/disqus.png)

注册 Disqus，获取 `shortname`，然后填入下方对应区域

https://help.disqus.com/customer/en/portal/articles/466208-what-s-a-shortname-
```yaml
disqus: 
  on: true
  shortname: 
```

## 2. 多说
![多说](/src/duoshuo.png)
http://duoshuo.com/create-site/

点击上方网址登陆你的多说，然后创建站点，在 `domain` 中填入你设定的域名前半部分

<blockquote class="note"> 比如完整域名是: <code>http://hellohexo.duoshuo.com</code>，只需填入 <code>hellohexo</code></blockquote>

```yaml
duoshuo: 
  on: true
  domain: 
```

<blockquote class='issue'>
    <a href="https://github.com/MOxFIVE/hexo-theme-yelee/issues/1" target="_blank">保留使用 Yilia 主题时的多说用户评论</a>
</blockquote>

<blockquote class='example'>
    <a href="http://moxfive.xyz/2015/09/29/duoshuo-style/" target="_blank">多说样式折腾记录 — 添加 UA 浏览器标识、旋转头像等</a>
</blockquote>

## 3. 友言
![友言](/src/youyan.png)
http://www.uyan.cc/index.php

`id` 中填写你的友言用户数字ID，注册后可进入后台管理查看

```yaml
youyan:
  on: true
  id: 
```

<blockquote class="note"> 友言服务在 Web 环境下运行，普通本地环境可能无法正常查看，请部署后在线上测试。</blockquote>
