---
layout: default
---

  <div id="post-list">
		{% for post in site.posts %}
		<div class="post-img-link-wrapper" data-content="{{ post.snippet }}">
		  <a class="post-img-link" href="{{ post.url | prepend: site.baseurl }}">
			  {% include story-list-img.html %}
		  </a>
		</div>
		{% endfor %}
  
  </div>

  <p class="rss-subscribe"><a href="">Subscribe</a></p>