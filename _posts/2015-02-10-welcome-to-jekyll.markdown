---
layout: post
title:  "基于自然演化的机构设计系统（一）"
date:   2018-03-22 22:08:54
categories: 构想
tags: 构想
excerpt: 一些初步想法
mathjax: true
---
##线索
某些诸如奇虾的古生物身体构造是随着自然演化不断改变，从而使自己不断适应环境的，例如奇虾的捕食器官从一根用于勾取猎物的触手演化为只用于滤食的触须，或是移动方式从游泳肢的屈伸变成依靠“鳍”这样的器官驱动身体，我们如果把这种动物理解为一个孤立的机械系统，这一系统内各功能性器官的演化过程或许可以看作是各机构的运动方式随着环境的变化而做出了相应的调整。

令我感兴趣的是，如果我们可以设计一套演算方法去模拟这种自然演化过程，将初始的机构输入，在随后的演化计算中不断优化自己的机构形态，最终得到一个新的东西，这或许会让我们找到一些有趣的结果！

![](https://babeljs.io/images/2.png)

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

```ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help

Block Mathjax 

$$
f(x) = ax + b
$$

Inline Mathjax $a \neq b$

