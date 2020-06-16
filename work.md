---
layout: page_nice
title: Work
title_diff: Work.
tags: work
permalink: "/work/"
meta_description: Want the proof? Here’s the pudding. Browse this page to see examples of my work.

---
Want the proof? **Here’s the pudding.**

Browse this page to see examples of projects I’ve worked on<span class = "asterisks">*</span>. <!--* -->

If you’d like to know more about these projects, or see further examples of my work, just ask<span class = "asterisks">**</span>. <!--** -->

<span class= "asterisksnote"><span class = "asterisks">*</span><!--* -->This does not include my ongoing cat-to-dog translation project.</span>

<span class= "asterisksnote"><span class = "asterisks">**</span><!--** -->Unfortunately, I will not be able to discuss my ongoing cat-to-dog translation project as it is top secret and deeply personal.</span>

<h2>Blogs</h2>

<div class="flexslider">
  <ul class="slides">
    {% for image in site.static_files %}
    {% if image.path contains 'blog-examples' %}
      <li>
      {% assign link = '#' %}
      {% for im_data in site.data.images %}
      {% if image.name contains im_data.name %}
        {% assign link = im_data.link %}
      {% endif %}
      {% endfor %}
      <a href="{{ link }}">
        <img src="{{ image.path }}" alt=""
             data-name="{{ image.name }}">
      </a>
      </li>
    {% endif %}
    {% endfor %}
  </ul>
</div>
<center> <span class= "asterisksnote">Click the images to read the blogs.</span> </center>

## Op-Ed / Editorial

<div class="flexslider">
  <ul class="slides">
    {% for image in site.static_files %}
    {% if image.path contains 'editorial-examples' %}
      <li>
      {% assign link = '#' %}
      {% for im_data in site.data.images %}
      {% if image.name contains im_data.name %}
        {% assign link = im_data.link %}
      {% endif %}
      {% endfor %}
      <a href="{{ link }}">
        <img src="{{ image.path }}" alt=""
             data-name="{{ image.name }}">
      </a>
      </li>
    {% endif %}
    {% endfor %}
  </ul>
</div>
<center> <span class= "asterisksnote">Click the images to read the articles.</span> </center>

## Websites

<div class="flexslider">
  <ul class="slides">
    {% for image in site.static_files %}
    {% if image.path contains 'website-examples' %}
      <li>
      {% assign link = '#' %}
      {% for im_data in site.data.images %}
      {% if image.name contains im_data.name %}
        {% assign link = im_data.link %}
      {% endif %}
      {% endfor %}
      <a href="{{ link }}">
        <img src="{{ image.path }}" alt=""
             data-name="{{ image.name }}">
      </a>
      </li>
    {% endif %}
    {% endfor %}
  </ul>
</div>
<center> <span class= "asterisksnote">Click the images to view the websites.</span> </center>

## Social Media

<div class="flexslider">
  <ul class="slides">
    {% for image in site.static_files %}
    {% if image.path contains 'social-media-examples' %}
      <li>
        <img src="{{ image.path }}" alt=""
             data-name="{{ image.name }}">
      </li>
    {% endif %}
    {% endfor %}
  </ul>
</div>

**Interest piqued?** Learn more about [my services]({{ site.baseurl }}/freelance-writer-edinburgh), or, if you’d like to work with me, [get in touch]({{ site.baseurl }}/contact).
