# Development Blog

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <p><a href="{{ post.url }}">{{ post.title }}</a> | {{ post.date | date: "%d-%m-%Y" }}</p>
    </li>
  {% endfor %}
</ul>