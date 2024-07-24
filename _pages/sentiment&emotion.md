---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title:  "Sentiments & Emotions"
subtitle: ""
show_sidetoc: true
header_type: hero #base, post, hero,image, splash
header_img: assets/images/emotions.png
header_title: "Sentiments & Emotions"
vega: true
---
# Sentiments & Emotions {#hide-sentiments-emotions}

## have you ever wondered how the tone of the football community you belong to is? 
 - We looked at the frequency of words with which football comments are spread.
<!-- Most frequent words -->
{% include one-column.html dimension="medium" title="We were amazed to see that the most common words are:" %}
{% include chart-selector.html dimension="medium" dataset="most_frequents" %}

>Among the most common words of all channels we note, as it could be expected, football clubs’ names, both national and international ( such as Juve, Intern, Milan, Napoli, Bologna, Bayern, Roma, Lazio etc.). We can also observe a lot of proper names and nicknames: this recalls our comparison between Twitch and a “digital pub”, an online space where you can find fellow football fans from all over the world and chat with them. Furthermore it can be seen that the tone is mostly positive, with people supporting their teams and laughing.<

Apart from exploring what individual people write, we wanted to check their interactions to see if communities are also created (or divided) around football in the digital world!
<!-- Section separator -->
<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

##### We used **_Pysentimiento,_** which allowed us to analyse both languages without the limitation of language; it is wonderful that communities can be united despite speaking different languages!
<!-- Sentiments statistics  -->
## Sentiment statistics
<vegachart schema-url="{{site.baseurl}}/assets/charts/PERCENTUALE SENTIMENT ITA.json" style="width: 100%"></vegachart>
- Italian channels.
<vegachart schema-url="{{site.baseurl}}/assets/charts/PERCENTUALE SENTIMENT ARG.json" style="width: 100%"></vegachart>
- Argentinian channels.



Accordingly, if we look at the tone of the channels, the Argentinian ones seem to be more negative than positive, with the majority of messages being labeled as neutral, while the Italian channels are balanced between the two sentiments.
<br> In addition, there is more variability inside the Italian channels with respect to Argentinian ones.

<!-- Section separator -->
<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

## Emotion statistics

Since we have six emotions for the Spanish language and four for the Italian, we plot the results into two different graphs.

<!-- Creating list with colors representing emotions -->
<div class="container mt-4">
  <ul class="list-group">
    <li class="list-group-item list-group-item-warning">
      We noticed that the following channels, AJGtv, Inter, Milan, and OCWSport, tend to present higher "joy" levels.
    </li>
    <li class="list-group-item list-group-item-danger">
      In contrast, the remaining channels(Controcalcio, HouseofCalcio, Juventibus, TeladoioTokyo, Assodiroma, daje, Fantacalcio, TVPlay) tend to show higher "anger" levels.
    </li>
    <li class="list-group-item list-group-item-success">
      The Argentinian channel Davoo tends to present high levels of ‘joy’ while La Cobra both 'disgust’ and ‘joy’.
    </li>
    <li class="list-group-item list-group-item-info">
      It is interesting also to see the scarcity of “sadness” as a negative emotion: people tend to be more angry than sad while discussing football.
    </li>
  </ul>
</div>
<br>
<!-- emotion_statistics charts -->
<vegachart schema-url="{{site.baseurl}}/assets/charts/PERCENTUALE EMOTION ITA.json" style="width: 100%"></vegachart>
<br>
<vegachart schema-url="{{site.baseurl}}/assets/charts/PERCENTUALE EMOTION ARG.json" style="width: 100%"></vegachart>

<!-- Section separator -->
<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>


### This brings us back to our initial question: Does football unite or divide? <br> This is why we wanted to deepen our analysis by identifying "friendly" or "enemy" communities within the channels. <br> Are you also curious to discover what we found?
<br>
Keep reading our story by clicking the button below or going to **Communities** section in the navigation bar.

<div class="container mt-3">
    <div class="row justify-content-center">
        <div class="col-auto">
            <!-- Button to the next page -->
            <a href="communities#communities" class="btn btn-primary">COMMUNITIES</a>
        </div>
    </div>
</div>