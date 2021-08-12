 <ul class="tag">
      {% for tag in page.tags %}
      <li>
        <a href="{{ site.url }}{{ site.baseurl }}/tags#{{ tag }}">
          {{ tag }}
        </a>
      </li>
      {% endfor %}
    </ul>
