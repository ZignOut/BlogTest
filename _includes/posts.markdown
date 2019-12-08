<h2>Posts</h2>

{% for post in site.posts %}
<div class="post">
    <h3>{{ post.title }}</h3>
    <img src="{{ post.img }}" alt="photo">
    <div>{{ post.excerpt }}</div>
    <a href="{{ post.url }}">read more>></a>
    <div class="author">{{ post.author }}</div>
    <div class="date">{{ post.date | date_to_string }}</div>
</div>
{% endfor %}