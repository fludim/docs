# Development Blog

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <p>{{ post.date | date: "%d-%m-%Y" }} <a href="{{ post.url }}">{{ post.title }}</a></p>
    </li>
  {% endfor %}
</ul>