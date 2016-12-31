---
layout: post
title:  preventDefault()
tags: Misc
categories: jQuery
order: 34
---

防止链接打开 URL：



~~~
$("a").click(function(event){
  event.preventDefault();
});
~~~
{: .language-ruby}



preventDefault() 方法阻止元素发生默认的行为（例如，当点击提交按钮时阻止对表单的提交）。