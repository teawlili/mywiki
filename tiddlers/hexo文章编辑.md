
## 新建文章  
> hexo n text1

## 新建草稿（draft）
draft 布局用于创建草稿，生成的文档存在于 source\_drafts\ 目录中，默认配置下将不会把该目录下的文档渲染到网站中。

新建一个草稿     
> hexo n draft draft_name

通过以下命令将草稿发布为正式文章：      
> hexo publish draft_name

## 查看已有草稿
> hexo --draft


## 文章折叠
在要显示的文字末尾添加如下代码实现文章在主页的折叠显示。

> <!-- more -->  
或者也可以将themes/next/_config.yml文件中的auto_excerpt字段值改为true


