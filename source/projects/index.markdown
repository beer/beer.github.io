---
layout: project
navbar: Projects
---

## New Pages

You can add pages anywhere in your blog source directory and they'll be parsed by Jekyll. The URL will correspond directly to the filepath, so `about.markdown` will become `site.com/about.html`. If you prefer the URL `site.com/about/` you'll want to create the page as `about/index.markdown`. Octopress has a rake task for creating new pages easily.

{% codeblock %}
rake new_page[super-awesome]
# creates /source/super-awesome/index.markdown
 
rake new_page[super-awesome/page.html]
# creates /source/super-awesome/page.html
{% endcodeblock %}
