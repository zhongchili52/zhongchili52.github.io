<!-- {% for link in site.data.navigation.main %}
  {% if link.right %}
    <a class="normal right" href="{{ link.url }}">{{ link.title }}</a>
    {% else %}
    <a class="normal" href="{{ link.url }}">{{ link.title }}</a>
  {% endif %}
{% endfor %} -->

<nav>
  <ul>
    <li><a href="{{ site.baseurl }}/">About Me</a></li>
    <li><a href="{{ site.baseurl }}/contact/">Contact</a></li>
  </ul>
</nav>

