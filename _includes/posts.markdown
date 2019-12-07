<h2>Posts</h2>

{% for post in site.data.posts %}
<div class="post">
    <h3>{{ post.title }}</h3>
    <img src="{{ post.image }}" alt="photo">
    <p>{{ post.text }}</p>
    <a href="{{ post.link }}">read more>></a>
    <div class="author">{{ post.name }}</div>
    <div class="date">{{ post.date }}</div>
</div>
{% endfor %}