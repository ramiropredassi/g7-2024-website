---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title:  "Communities"
subtitle: "An insight of communities inside twitch channels"
show_sidetoc: true
header_type: hero #base, post, hero,image, splash
header_img: assets/images/graph.png
header_title: "Communities"
vega: true
---
# communities {#hide-communities}

## Have you thought the tone could relate to the people you interact with and the community structure?

<!-- Pyvis interaction graph -->
<div class="graph-container mt-1">
    <iframe src="{{ '/assets/charts/roma.html' | relative_url }}" width="100%" height="400px" frameborder="0" allowfullscreen></iframe>
</div>

- We, too! For this reason, we decided to study the social balance of our channels to identify if communities were created behind the platform and of what nature (positive, negative)!
<br>

<!-- Section separator -->
<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

## Social balance
<vegachart schema-url="{{site.baseurl}}/assets/charts/socialbalance.json" style="width: 100%"></vegachart>
<br>
>We note something interesting: different to other channels, Juventibus and HouseofCalcio do not have triads. Unlike what we were expecting, this reveals that these channels do not present social balance, and, therefore, their communities **_tend to be more fragmented without strong links between the users._**
<br>From the other channels that present triads, apart from AssodiRoma and LaCobra, which revealed a lower social balance, and ACMilan and AJGtv, which presented higher outcomes, we saw that the rest of the channels have a fair social balance. In other words, although it is possible to find triads, **_this does not mean that the groups are cohesive enough._** 

**_You might be wondering, as we did, why the number of triads tended to be small!_**<br>
We have come up with a tentative explanation concerning the time frame of our analysis. Since Twitch is a live stream platform and, therefore, most of the time, people respond to what Streamer says in a specific moment, we could expect that by increasing the time frame, it would be possible to trace more interactions and, therefore, the formation of potential triads.
#### If you are wondering what triads are?

<div class="container mt-3">
    <div class="row justify-content-center">
        <div class="col-auto">
            {% capture triads %}
            {% include_relative snippets/triads.md %}
            {% endcapture %}
            {% include modal-component.html title="Triads" content=triads id="triads" size="md" %}
        </div>
    </div>
</div>

<!-- Section separator -->
<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

## Assortativity
Apart from examining the **_"cohesiveness"_** of the network, we wanted to know if "similar" nodes tended to connect "with each other”. 
##### Have you ever heard that "Birds of a feather flock together"? 
In social network analysis, this is called homophily and refers to the tendency of nodes to interact with those who are similar to them. 
For this reason, we measured the assortativity of each channel –to identify if, for instance, the users who displayed a positive tone tended to interact with others who used a similar tone in their comments.
<!-- Assortativity charts with vega -->
<br>
<vegachart schema-url="{{site.baseurl}}/assets/charts/ASSORTATIVITY ITA.json" style="width: 100%"></vegachart>
<br>
<vegachart schema-url="{{site.baseurl}}/assets/charts/ASSORTATIVITY ARG.json" style="width: 100%"></vegachart>
<br>
1. We noticed that for AcMilan, AssodiRoma, Inter, even if mild, display some levels of homophily‼ Differently is the case of Daje, FantaCalcio and TVPlay, which displayed a negative assortativity; the nodes of these networks tend to connect with dissimilar nodes; **_this is what we call heterophily!_**
2. However, there are other channels that are close to 0, which suggests that interaction does not follow any pattern.
3. Finally, House of Calcio presents an assortativity equal to 0 which can be interpreted as random connectivity without displaying high or low levels of homophily/heterophily.

>This analysis revealed something interesting: Depending on the channel, users can also be different and, therefore, display different behaviours!
> Despite being digital networks, we are talking about 'real' humans, and, therefore, their networks can reflect dynamics that we see in society; networks are not always the same; they change through time and adapt to different circumstances!




<!-- Section separator -->
<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

### This brings us back to our initial question: Does football unite or divide? This is why we wanted to deepen our analysis by identifying "friendly" or "enemy" communities within the channels.
<br>
You can see our **Conclusions** by clicking the button below or by selecting the section in the navigation bar.

<div class="container mt-3">
    <div class="row justify-content-center">
        <div class="col-auto">
            <!-- NEXT PAGE BUTTON -->
            <a href="conclusion#conclusion" class="btn btn-primary">CONCLUSION</a>
        </div>
    </div>
</div>