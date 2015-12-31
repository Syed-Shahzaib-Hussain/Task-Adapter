---
layout: default
top_level_menu_weight: 30
title: Blog
permalink: /blog/
---
<div id="wrapper" class="clearfix">
<!-- <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p> -->
  <div id="content-blog" class="grid col-620">
    <ul class="post-list">
      {% for post in site.posts %}
        

          <h2>
            <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
          </h2>
         <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
          <p>{{post.excerpt}}</p>
          <span>{{ post.categories | join: ' ' }}</span>
      {% endfor %}

    </ul>
  </div>

  <div id="widgets" class="grid col-300 fit">
      
      <div id="categories-5" class="widget-wrapper widget_categories"><div class="widget-title"><h3>Categories</h3></div>   <ul>
    <li class="cat-item cat-item-9"><a href="{{ site.baseurl }}/category/atlassian-jira/">atlassian jira</a>
  </li>
    <li class="cat-item cat-item-15"><a href="{{ site.baseurl }}/category/basecamp/">basecamp</a> 
  </li>
    <li class="cat-item cat-item-16"><a href="{{ site.baseurl }}/category/basecamp-classic/">basecamp classic</a>
  </li>
    <li class="cat-item cat-item-14"><a href="{{ site.baseurl }}/category/development/">development</a>
  </li>
    <li class="cat-item cat-item-13"><a href="{{ site.baseurl }}/category/github/">github</a>
  </li>
    <li class="cat-item cat-item-12"><a href="{{ site.baseurl }}/category/mantisbt/">mantisbt</a>
  </li>
    <li class="cat-item cat-item-11"><a href="{{ site.baseurl }}/category/microsoft-project/">microsoft project</a>
  </li>
    <li class="cat-item cat-item-7"><a href="{{ site.baseurl }}/category/redmine/">redmine</a>
  </li>
    <li class="cat-item cat-item-8"><a href="{{ site.baseurl }}/category/redmine-java-api/">redmine java api</a>
  </li>
    <li class="cat-item cat-item-10"><a href="{{ site.baseurl }}/category/release/">release</a>
  </li>
    <li class="cat-item cat-item-1"><a href="{{ site.baseurl }}/category/uncategorized/">Uncategorized</a>
  </li>
      </ul>
  </div>
        </div>
  
</div>
