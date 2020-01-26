# HI MY WORD
MY FISRT POST
如果想在文章里面加入图片，需要先把图片上传
然后在文章中以如下字符串来加入：
![Image description](images/filename.jpg
如果想加博客文章索引目录，输入下面两行
1. TOC
{:toc}
之前写的博文标题（以#标志的一级标题）就会自动出现在目录里，并且自带超链接。

如果想加入数学符号，可以用LaTeX的格式。

首先在 _config.yml文件中进行设置，将use_math进行简单的修改，变成这样：
use_math: true
只需要在字符串前后各加一个  $ ， 比如 $\sum_n (x)$ , 或者想让它单行显示的时候，在上下两行各加$$，像这样：

$$
\sum_n (x)
$$
