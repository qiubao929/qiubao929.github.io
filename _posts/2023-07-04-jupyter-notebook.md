---
layout: post
title: cnki page
date: 2023-07-04 08:57:00-0400
description: an example of a blog post with jupyter notebook
tags: formatting jupyter
categories: sample-posts
giscus_comments: true
related_posts: false
---


{% endraw %}

中国知网首页((https://kns.cnki.net/kcms2/author/detail?v=uzDkwlsKYf-aayv5CcxSIjik_px-tDYUG5dkv1LFcqPRiCchuQGs_h-pcb_gRa5dMw92XQSLghKgobffeXZT18UScgcbVUSiXR8i2EhqmybrSW3J-lMprxckGj0FQ8EM&uniplatform=NZKPT&language=CHS)) 


{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/blog.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/blog.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}

Note that the jupyter notebook supports both light and dark themes.
