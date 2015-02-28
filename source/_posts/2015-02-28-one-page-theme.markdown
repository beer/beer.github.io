---
layout: post
bootstrap_theme_url: http://bootswatch.com/slate/bootstrap.min.css
title: "Pick a Theme for Only One Page"
date: 2015-02-28 14:16:45 +0800
comments: true
categories: [octopress,bootstrap]
---

As you can see on this page, it is possible to have a different theme for a given page or post (this one is the mighty [slate](http://bootswatch.com/slate/bootstrap.min.css)) !

The Trick
We will use a [front-matter](http://jekyllrb.com/docs/frontmatter/) variable to select the theme to use. First, adapt `source/_includes/custom/head.html`:

``` html source/_includes/custom/head.html
<!-- ... -->
{ % if page.bootstrap_theme_url %}
  	<link href="{{ page.bootstrap_theme_url }}" rel="stylesheet" type="text/css">
{ % else %}
  	<link href="{{ root_url }}/assets/bootstrap/dist/css/bootstrap.min.css" rel="stylesheet" type="text/css">
  	<link href="{{ root_url }}/assets/bootstrap/dist/css/bootstrap-theme.min.css" rel="stylesheet" type="text/css">
{ % endif %}
<!-- ... -->
```

Now, the Bootstrap theme will be choosen depending on `page.bootstrap_theme_url`. As an example, here is the front of this page:

{% codeblock example front %}
---
layout: post
bootstrap_theme_url: http://bootswatch.com/slate/bootstrap.min.css
title: "pick a theme for only one page"
comments: true
categories: octopress
---
{% endcodeblock %}
