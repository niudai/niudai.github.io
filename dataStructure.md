---
layout: index
permalink: /dataStructure/
---
<div>
      {% for post in site.categories.data %}
      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>
      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
      {% endfor %}
</div>
## 联系我

邮箱: [1244453736@qq.com](mailto:1244453736@qq.com)

微信: 18324748963