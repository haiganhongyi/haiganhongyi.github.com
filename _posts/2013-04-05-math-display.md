--- 
layout: post
title: "在我的主页上显示数学公式吧"
tags: 
- 数学公式
status: publish
type: post
published: true

---

见识了许多主页上可以显示数学公式，我的目的...嘿嘿
$$
\sum_i|x_i – s|^p
$$
显示了嘛？
第三次发问哦？
yes，that is working！
使用方法[链接](http://cyukang.com/2013/03/03/try-mathjax.html)：
即第一步，需要使用[mathjax](http://www.mathjax.org/) 的官方说明
须在default.html中添加一行script
<pre>
<script type="text/javascript"
   src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
   </script>
</pre>
主要问题在于必须将rdiscount设置改为kramdown(在config.yml配置文件中)
tks for google！