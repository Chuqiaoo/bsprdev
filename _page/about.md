
<!------->
<!--<!--type: pages-->-->
<!--layout: page-->
<!--title:  About-->
<!--<!--date:   2018-05-30-->-->


<!------->

<!--The British Society for Proteome Research (BSPR), is a registered incorporated charity (Registered Company Number 6319769, UK Charity Number 1121692) and aims to advance the science of proteomics, to further public education therein and to promote study and research work in proteomics and related subjects for the public benefit.-->

<!--The BSPR represents both the Human Proteome Organization (HUPO) and the European Proteomics Association (EuPA) in the UK and is affiliated to the Society of Biology.-->


<!--Aim-->
<!--The objectives of the British Society for Proteome Research (BSPR) are to advance the science of proteomics and to promote the study and research work in this and related areas for the benefit of all. It enables scientists working in this field to keep up-to-date with current developments both nationally and internationally and to meet and exchange ideas with other workers. Unlike many learned societies we have members from a wide range of organisations including industry and the health service, as well as research and academic institutions.-->


<!--BSPR Memorandum of Association-->


---
layout: page
title: About
comments: true

---

This website is built with Jekyll and "Affiliates" (a Jekyll Template designed & developed by WowThemes.net). It is meant for demonstration purposes, so you can have an idea of how this theme looks in action so no real content can be found. Affiliates template for Jekyll is compatible with Github pages, in fact even this demo is created with Github Pages and hosted with Github. This page in example shows a page layout.

**License & Download**

"Affiliates" for Jekyll is designed and developed by WowThemes.net and it is *free* for personal use.

<a href="https://gum.co/affiliates-jekyll-template" target="_blank">Download - Affiliates Jekyll Theme</a>

![jekyll template mediumish]({{site.baseurl}}/assets/images/theme1.jpg)

![jekyll template mediumish]({{site.baseurl}}/assets/images/theme2.jpg)

![jekyll template mediumish]({{site.baseurl}}/assets/images/theme3.jpg)

![jekyll template mediumish]({{site.baseurl}}/assets/images/theme4.jpg)

#### Features

- Built for Jekyll
- Compatible with Github pages
- Featured Posts
- Index Pagination
- Post Categories
- Prev/Next Link
- Category Archives (this is not yet compatible with github pages though)
- Integrations:
    - Disqus Comments
    - Google Analaytics
    - Mailchimp Integration
    - Sharethis Integration
    - Formspree.io Contact
- Design Features:
    - Bootstrap v4.0.0-alpha.6
    - Font Awesome
    - Masonry
- Layouts:
    - Default
    - Post left sidebar
    - Post right sidebar
    - Page
    - Archive

#### How to Use

If you aren't familiar with Jekyll yet, you should know that it is a static site generator. It will transform your plain text into static websites and blogs. If you are a beginner we recommend you start with [Jekyll's Docs](https://jekyllrb.com/docs/installation/){:target="_blank"}. Now if you know how to use Jekyll, let's move on to using Affiliates template in Jekyll:

[Download](https://gum.co/affiliates-jekyll-template){:target="_blank"} or Fork *Affiliates for Jekyll*.
- In your local project, open <code>_config.yml</code>. If your site is in root, for <code>baseurl</code>, make sure this is set to <code>baseurl: /</code>. Also, change your Google Analytics code, Disqus username, Authors, Mailchimp, ShareThis code (https://www.sharethis.com/) etc.
- Affiliates requires 2 plugins:
    - <code>$ gem install jekyll-paginate</code>
    - <code>$ gem install jekyll-archives</code>.
- Locate the files and customize:
    - header & footer in <code>default.html</code>.
    - homepage in <code>index.html</code>
    - contact form in <code>contact.html</code> (https://formspree.io/)
    - post sidebar in <code>includes/sidebar.html</code>
    - sign up form in <code>includes/newsletter.html</code>
- Start blogging by adding your .md files in <code>_posts</code>. You will see in examples in the download.
- YAML front matter
    - post featured - <code>featured:true</code>
    - post featured image - <code>image: assets/images/mypic.jpg</code>
    - page comments - <code>comments:true</code>
    - meta description (optional) - <code>description: "this is my meta description"</code>

YAML Post Example:
<pre class="highlight">
---
layout: post
title:  "We all wait for summer"
author: john
categories: [ Jekyll, tutorial ]
image: assets/images/5.jpg
featured: true
---
</pre>

YAML Post Sidebar Right Example:
<pre class="highlight">
---
layout: post-sidebar-right
title:  "We all wait for summer"
author: john
categories: [ Jekyll, tutorial ]
image: assets/images/5.jpg
featured: true
---
</pre>

YAML Page Example
<pre class="highlight">
---
layout: page
title: Affiliates Template for Jekyll
comments: true
---
</pre>