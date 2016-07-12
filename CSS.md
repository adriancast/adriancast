---
layout: page
title: Css
permalink: /css/
---
{% for post in site.posts %}

<div class="col-md-12 post">
			<div class="row">

				<div class="col-md-12 textPost" style="color:black;">
					<h2><a class="post-link" href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
				    <p>{{ post.content }}</p>

				</div>

			</div>

		</div>

{% endfor %}
