
MEER fans is a global open source community, focusing on blockchain technology exchange and promotion,especially block-DAG technology.

## 如何写文章

本 github 仓库与 MEER fans 官网直接对应。在本仓库中做的改动会立即体现在官网上（不过一般因为Jekyll需要时间构建或是缓存方面的缘故，可能会有一段时间的延迟）。

在 MEER fans 官网上添加新文章的方法如下：

在 _post 目录为新文章创建一份空白文件。文件名的形式必须是 yyyy-mm-dd-{title}.md，其中 {title} 是文章的标题。
将文章内容全部粘贴进刚创建的文件中。
在文件头部添加 yaml 格式的描述信息。如下面的例子所示：

``` bash
     ---
     layout: post
     title:  标题  // 标题配置
     date:   2016-08-27 01:08:00 +0800     // 时间配置
     author: xxxxx  // 作者配置
    ---
    我是正文。我是正文。我是正文。我是正文。我是正文。我是正文。
```

其中：

layout 必须填 post。

categories 是文章所属的分类信息，比如论文的分类是 Paper。一篇文章可以属于多个分类。但是一般只填一个分类。

image 是文章在首页显示用的封面图片的 URL。

title 是文章标题，这个标题会体现在浏览器上面。也可以不填，不填的话则会采用文件名中的标题信息。如果填的话注意要加英文双引号。

tag 是文章标签。一篇文章可以有多个标签。一边建议一篇文章至少要有一个专属的标签，方便筛选。
