title:  hexo的基本用法
category: 
- Help  

tag:
- hexo
- help
---


[下面是官方的解释](http://hexo.io/docs/writing.html)，但是实际使用时候还需要参考themes/xxx/layout的命名

You can configure all post configuration in the front-matter. The following is predefined settings.

<!--more-->

Setting Description Default
layout  Layout  post/page
title   Title   
date    Published date  File created date
updated Last updated date   File last updated date
comments    Enables comment feature for the post    true
tags    Tags (Not available for pages)  
categories  Categories (Not available for pages)    
permalink   Overrides the default permalink of the post Filename

------
Hexo supports categories and tags. Categories and tags are only supported in posts and have to be set in the front-matter. For example:

```
categories:
- Diary
tags:
- PS3
- Games
```
#代码高亮
```
    int main(me)
    {
        auto who  = 程序员;
        auto I   = 养喵人;
        auto am  = 非典型c++码农;
        关注 = python和移动互联网;
        业余爱好  = 敲敲python，学学韩语，上上公开课。
    }
```

http://howiewang.github.io/categories/Web/
http://howiewang.github.io/categories/Help/

----
###几个已经存在的窝

* [幸福罗盘](http://happyaround.com)
* [浩爷爱读书](http://sothislove.com)
* [咱家的正牌喵星人](http://howiewang.github.io/LuLu/)

-----
欢迎讨论，欢迎交流，欢迎留言^-^