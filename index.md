{% for post in site.posts %}
  <h1>{{ post.title }}</h1>
  <p>{{ post.excerpt  | remove: '<p>' | remove: '</p>' }} <a href="{{ post.url }}">[...]</a></p>
{% endfor %}
