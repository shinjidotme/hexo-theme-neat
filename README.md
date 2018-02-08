# 摸了

# hexo-theme-neat

随意写了一个主题，很简陋，很多功能都没有:P，[demo](http://blog.shinji.me)

看心情跟时间偶尔更新，不断更新设计和功能

如果你只是喜欢这个设计，没有初级的编程能力，对 hexo 不甚了解，那么，不建议你使用本主题。

## 几个注意点
### 文章页头图
文章内添加 Front-matter, ```cover：imgsrc```

### 评论系统
仅支持[hypercomments](https://www.hypercomments.com/)（因为其他的都太丑了）,主题配置文件里添加你的 ID 即可，ID在你进入 admin 页面，点击右上角齿轮图标，新创建 widget 后即可在下图标注位置中看到

### tags页面与category页面

首先在主题配置文件中打开 menu 相关项，然后

```
hexo new page tags
hexo new page categories
``` 
会新创建两个文件夹tags/categories,修改各自的 index.md Front-matter

```bash
# tags
layout: tags.ejs

# categories
layout: categories.ejs

# 如果某篇需要关闭评论，markdown里设置Front-matter
comments: flase
```
