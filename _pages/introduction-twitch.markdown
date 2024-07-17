---
layout: default-full
title: "Introduction"
subtitle: "Everything you need to know about our project"
show_sidetoc: true
header_type: hero #base, post, hero,image, splash
header_img: assets/images/Atlante_cover.jpeg
header_title: "Intro to Birra, Fernandito e Pallone"
vega: true
---

[//]: # (Twitch description section)


{% capture stragi_all %}
    {% include_relative snippets/mappa-stragi-intro.md %}
{% endcapture %}


[//]: # (Why we have choose Twitch section)
{% capture introduction_content %}
    {% include_relative snippets/introduction.md %}
{% endcapture %}

{% include one-column.html dimension="small" content=introduction_content %}


[//]: # (Correlation section)
<br>
{% capture timeline_stragi %}
{% include_relative snippets/chart-timeline.md %}
{% endcapture %}

{% include one-column.html dimension="small" content=timeline_stragi %}

[//]: # (Twitch metrics)
<div class="bg-color bg-color-full py-3 my-5">
    {% include one-column.html dimension="small" title="I numeri delle stragi per matrice" %}
    {% include big-numbers-cards.html data="morti-matrice" number="Morti" description="Matrice" %}
</div>

[//]: # (Statistics by chanel)
{% capture introduction_images %}
{% include_relative snippets/gallery-images.md %}
{% endcapture %}

{% capture section_1_content %}
    {% include_relative snippets/section-1.md %}
{% endcapture %}

{% include two-columns.html col-one=introduction_images col-two=section_1_content %}
