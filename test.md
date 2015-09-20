---
layout: default
published: true
---








  <div class="content">
        <div class="content-center">
      <div class="container-fluid">
      <div class="row">


		{% for post in site.posts %}
		<div class="col-md-4 col-sm-3 col-xs-4">
          <a href="{{ post.url }}"><img class="img-responsive" src="/img/thumb/{{ post.photo }}" alt="img"/></a>
        </div>

		{% endfor %}

	</ul>
</div>
</div>
</div>
