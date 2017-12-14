---
layout: default
---

  <div id="post-list">
		{% for post in site.posts %}
		<div>
		  <a class="post-img-link-wrapper" data-content="{{ post.snippet }} href="{{ post.url | prepend: site.baseurl }}">
			  {% include story-list-img.html %}
		  </a>
		</div>
		{% endfor %}
  
  </div>