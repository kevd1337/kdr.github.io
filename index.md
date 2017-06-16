{% for post in site.posts %}
  <h1>{{post.title}}</a>
  <p>{{ post.excerpt }} <a href="{{ post.url }}">[...]</a></p>
{% endfor %}
