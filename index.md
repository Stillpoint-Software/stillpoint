---
layout: default
---

{% include sections.html %}
{% include services-content.html %}
<div class="container">
    <div class="row">
        <div class="col col-12 col-d-10 col-m-12 push-m-0 push-d-1">
            <div class="contaniner__inner">
                <div class="row grid">
                    {% if site.posts.size > 0 %}
                    {% for post in site.posts limit: 3%}
                    {% include article-content.html %}
                    {% endfor %}
                    {% endif %}
                </div>
            </div>
        </div>
    </div>
</div>
