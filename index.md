---
layout: default
---

  <div id="post-list">
		{% for post in site.posts %}
		
		  <a class="post-img-link" href="{{ post.url | prepend: site.baseurl }}">
		  <div class="post-img-link-wrapper" data-content="{{ post.snippet }}">
			  {% include story-list-img.html %}
			  </div>
		  </a>
		
		{% endfor %}
  
  </div>