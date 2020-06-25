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

**If you’d like to know more about these projects**, or see further examples of my work, [just ask]({{ site.basurl }}/contact)<span class = "asterisks">**</span>. <!--** -->

<span class= "asterisksnote"><span class = "asterisks">*</span><!--* -->This does not include my ongoing houseplant-to-human translation project. </span>

<span class= "asterisksnote"><span class = "asterisks">**</span><!--** -->Unfortunately, I will not be able to discuss my ongoing houseplant-to-human translation project as it is top secret and deeply personal. </span>

<h2>Blogs</h2>

I can help you to reach new customers online and retain existing ones, using purposeful blog content that readers will value.

<div class="flexslider">
  <ul class="slides">
    {% for image in site.data.images %}
    {% if image.name contains 'blog-examples' %}
      <li>
      {% if image.link %}<a href="{{ image.link }}">{% endif %}
        <img src="{{ site.baseurl }}/{{ image.name }}.png" alt=""
             data-name="{{ image.name }}">
      {% if image.link %}</a>{% endif %}
      </li>
    {% endif %}
    {% endfor %}
  </ul>
</div>
<center> <span class= "asterisksnote">Click the images to learn more.</span> </center>

## Op-Ed / Editorial

Whether you’re a businessperson, a lawyer or a deep-sea diver, publishing articles in credible outlets will boost your profile.

I can ghost-write op-eds that deliver your arguments with gravitas. If you’d like extra support securing editorial opportunities, I can also lend a helping hand.

<div class="flexslider">
  <ul class="slides">
  {% for image in site.data.images %}
  {% if image.name contains 'editorial-examples' %}
    <li>
    {% if image.link %}<a href="{{ image.link }}">{% endif %}
      <img src="{{ site.baseurl }}/{{ image.name }}.png" alt=""
           data-name="{{ image.name }}">
    {% if image.link %}</a>{% endif %}
    </li>
  {% endif %}
  {% endfor %}
  </ul>
</div>
<center> <span class= "asterisksnote">Click the images to learn more.</span> </center>

## Websites

I can make sure your website performs the way you want it to, with enticing copy and a user-friendly structure to keep your visitors sticking around. High bounce rates begone!

<div class="flexslider">
  <ul class="slides">
  {% for image in site.data.images %}
  {% if image.name contains 'website-examples' %}
    <li>
    {% if image.link %}<a href="{{ image.link }}">{% endif %}
      <img src="{{ site.baseurl }}/{{ image.name }}.png" alt=""
           data-name="{{ image.name }}">
    {% if image.link %}</a>{% endif %}
    </li>
  {% endif %}
  {% endfor %}
  </ul>
</div>

## Social Media

I can build a loyal following with social media posts that give your brand a winning personality. I’ll develop a tailored social strategy tailored and deliver content in weekly, bi-weekly or monthly instalments.

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
