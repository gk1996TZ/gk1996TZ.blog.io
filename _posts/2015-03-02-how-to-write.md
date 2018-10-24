---
layout: post
title: javascriptc创建对象的六种方式
date: 2018-10-24
categories: blog
tags: [标签一,标签二]
description: 文章金句。
---
前言:

JavaScript是一门面向对象的语言,所以创建对象就是必不可少的,这里我就要讲创建对象的六种方式

第一种方式:利用Object构造函数创建对象
上代码:

<script type="text/javascript">
//创建对象的第一种方式:利用Object构造函数创建对象
var person=new Object();
person.name="helloworld";
person.age=10;
person.info=function(){
alert(this.name+this.age);

}
person.info();
</script>

这种方法是基于已经存在的Object对象去扩充他的属性和方法,缺点也很明显就是会有大量的重复代码,创建一个对象都有这些共同的代码





