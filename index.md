<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>




  {% for post in site.posts %}
  * [{{ post.title }}]({{ site.baseurl }}{{ post.url }}")
    * {{ post.date | date: "%B %d, %Y" }}
  {% endfor %}
