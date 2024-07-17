---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default-full
title: "Home"
subtitle: "Beer, Fernandito and Football"
show_sidetoc: true
header_type: hero #base, post, hero,image, splash
header_img: assets/images/logo intro.png
header_title: "Birra, Fernandito e Pallone"
---


[//]: # (il team)
{% capture fulbo_content %}
    {% include_relative snippets/fulbo.md %}
{% endcapture %}

{% include one-column.html dimension="small" content=fulbo_content %}

[//]: # (links section)
<div class="row pb-5">
    <div class="col-md-12 col-sm-12">
        <div class="card-container">
            {% for image in site.data.home-cards %}
            <div class="card" style="width: 18rem;">
                    <a href="{{site.baseurl}}{{ image.path}}">
                    <div class="card-img" ><img src="{{site.baseurl}}{{ image.url}}" class="card-img-top" alt="{{ image.name }}">
                    </div>
                    <div class="card-body">
                        <h5 class="card-title">{{ image.name }}</h5>
                        <p class="card-text">{{ image.description }}</p>
                    </div>
                    </a>    
            </div>
            {% endfor %}
        </div>
    </div>
</div>
