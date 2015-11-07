---
layout: post
title:  "Rust 学习笔记"
date:   2015-10-23 00:52:34
categories: jekyll update
---
开始学习Rust Good luck

{% highlight rust %}
fn main () {
    println!("hello {}!", "world");
    let str = format!("float {:.*}", 2, 123.44411); :.*表示浮点，2是精度
    println!("{}", str);
}
{% endhighlight %}

