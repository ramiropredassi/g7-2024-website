---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title:  "Twitch"
subtitle: "Everything you need to know about our project"
show_sidetoc: true
header_type: hero #base, post, hero,image, splash
header_img: assets/images/Inside_Out_film_2015.jpg
header_title: "Twitch"
---

## Do you also watch football in the company of other fanatics?
 - Have you ever felt that strangers could become close friends after watching a match?
 - Have you cried or celebrated the result of your football team in the presence of other people?
 - Do you enjoy chatting and sharing your opinions during a game?
<br> 

#### **_We all love to do that, so we used to watch our favourite matches in a pub!_**

<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

The new technologies have contributed to bringing these experiences to the comfort of your home!.<br>
##### **_Twitch_** is an interactive streaming service that, in addition to exploring opinion threads, allows us to capture user interactions – even if people are in different parts of the world!
>Encouraged to understand if football is an element of union or division, we found it interesting to explore how communities grew up on Twitch, how they interact, and how they influence each other.

<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

## Why football? Besides our passion for this sport, this is also the most popular sport today!
With its 5 billion fans around the world (FIFA 2021), football has become a true social phenomenon that can be studied from different points of view. This discipline can also analyse different aspects of society.

<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

Even if we want to explore what happens in each club, country, and continent, limiting our initial search to two cases, Italy 🇮🇹 and Argentina 🇦🇷, is pertinent.
<br>Not only do we love ❤️ these countries' football clubs, but they are nations that share a common history despite being separated by the ocean. 
<br>Italians and Argentinians are passionate about football 

{% capture whyArgIT %}
{% include_relative snippets/whyArgIT.md %}
{% endcapture %}

{% include modal-component.html title="Why Italy and Argentina" content=whyArgIT id="whyArgIT" size="xl" %}

Both countries also share common historical roots, and there are numerous examples of players who connect both football realities!
<br>Although they share a similar football history, Twitch dynamics are not the same in both countries, and we also found it interesting to capture this difference.
- In Argentina, we have focus  in two main channels with the most views in average, between the both they have a stable **87.000 users**; in Italy, there are many more, so we used Twitchmetrics to select the most popular based on the number of views!
  - ![BAR CHART](path/to/bar-chart.png)
- Although the Atlantic geographically separates these two countries, digitality reduces this natural border; thereby, we could see a budding demonstration of our thesis! Football generates a relationship because Italians and Argentines actively participate in channels that do not limit their geographical borders.
  - ![GRAFICO](path/to/grafico.png)
- To explore whether our intuition was true in this "digital pub", Twitch, we decided to perform two analyses: sentiment analysis and social network analysis.
