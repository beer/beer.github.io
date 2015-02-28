---
layout: post
title: "first octopress post"
date: 2015-02-27 21:08:08 +0800
comments: true
categories: 
---

{% img http://placekitten.com/890/280 %}
<!-- more -->
This is an H1
=============

This is an H2
-------------

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> >Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");


1.  Bird
4.  McHale
3.  Parish

- title
- tiele
- sa

*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.
    
    
This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

[id]: http://example.com/  "Optional Title Here"

This is [an example] [id] reference-style link.

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

Use the `printf()` function.

``There is a literal backtick (`) here.``



{% img http://placekitten.com/890/280 %}
{% img left http://placekitten.com/320/250 Place Kitten #2 %}
{% img right http://placekitten.com/300/500 150 250 Place Kitten #3 %}
{% img right http://placekitten.com/300/500 150 250 'Place Kitten #4' 'An image of a very cute kitten' %}

![Alt text](http://placekitten.com/320/250 "Optional title")

{% video http://s3.imathis.com/video/zero-to-fancy-buttons.mp4 640 320 http://s3.imathis.com/video/zero-to-fancy-buttons.png %}

{% pullquote %}
Surround your paragraph with the pull quote tags. Then when you come to
the text you want to pull, {" surround it like this "} and that's all there is to it.
{% endpullquote %}

{% codeblock Javascript Array Syntax lang:js http://j.mp/pPUUmW MDN Documentation %}
var arr1 = new Array(arrayLength);
var arr2 = new Array(element0, element1, ..., elementN);
{% endcodeblock %}

