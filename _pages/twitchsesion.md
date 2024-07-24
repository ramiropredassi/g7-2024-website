---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title:  "Twitch"
subtitle: "Everything you need to know about our project"
show_sidetoc: true
header_type: hero #base, post, hero,image, splash
header_img: assets/images/twitch.png
header_title: "Twitch"
vega: true
---

## Do you also watch football in the company of other fanatics?
- Have you ever felt that strangers could become close friends after watching a match?
 - Have you cried or celebrated the result of your football team in the presence of other people?
 - Do you enjoy chatting and sharing your opinions about a game?
<br>

<!-- Section separator -->
<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

New technologies have contributed to bringing these experiences to the comfort of your home!
    It's like having the collective experience of watching your favourite match in a pub, but online, and without borders!<br>
##### We chose to investigate **_Twitch_**, an interactive streaming service that, in addition to exploring opinion threads, allows us to capture user interactions – even if people are in different parts of the world!

<!-- interview quote -->
<style>
  .highlight-quote {
    background-color: #f8f9fa;
    border-left: 5px solid #007bff;
    padding: 20px;
    margin: 20px 0;
    border-radius: 5px;
  }
</style>

<div class="container mt-4">
  <div class="highlight-quote">
    <p class="mb-0">“The beautiful thing about Twitch is that you chat with people, dialogues arise, and you do not feel alone.”</p>
    <footer class="blockquote-footer">With these words, the streamer LucullusGames refers to Twitch.</footer>
  </div>
</div>


>Encouraged to understand if football is an element of unity or division, we found it interesting to explore how communities grew up on Twitch, how they interact, and how they influence each other.

<!-- Section separator -->
<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

Although they share a similar football history, Twitch dynamics are not the same in both countries, and we also found it interesting to capture this difference.<br>
**_In Argentina, there are two main channels with a larger active user' base while in Italy there are more channels but smaller, so we used  Twitchmetrics to select the most popular based on the number of views!_**

<!-- table with statistics -->
#####  Unique users in the channels that have been selected:
<div class="container mt-3">
  <div class="row justify-content-center">
    <div class="col-auto">
      <div class="table-responsive">
        <table class="table table-striped table-bordered table-hover" style="font-size: 25px;">
          <tr>
            <td align=center> 87.000 <br>(Argentinian channels)</td>
            <td align=center> 13.500 <br>(Italian channels)</td>
          </tr>
        </table>
      </div>
    </div>
  </div>
</div>

##### Messages analyzed by language: 

<!-- table with statistics -->
<div class="container mt-3">
  <div class="row justify-content-center">
    <div class="col-auto">
      <div class="table-responsive">
        <table class="table table-striped table-bordered table-hover" style="font-size: 25px;">
          <tr>
            <td align=center>2.5 Million (Spanish)</td>
            <td align=center> 1.5 Million (Italian)</td>
          </tr>
        </table>
      </div>
    </div>
  </div>
</div>

<!-- Section separator -->
<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

Although the Atlantic geographically separates these two countries, the digital world reduces this natural border; Consequently, we could see a budding demonstration of our thesis!.

<!-- Distance map -->
<div class="container mt-3">
    <div class="row justify-content-center">
        <vegachart schema-url="{{site.baseurl}}/assets/charts/arg_ita.json" style="width: 100%"></vegachart>
    </div>
</div>
<br>   

#### FOOTBALL GENERATES A RELATIONSHIP AS ITALIANS AND ARGENTINES ACTUALLY PARTICIPATE IN CHANNELS THAT DO NOT LIMIT THEIR GEOGRAPHICAL BORDERS.<br>

<!-- Button to see heatmap of interactions -->
<div class="container mt-3">
    <div class="row justify-content-center">
        <div class="col-auto">
            {% capture correlations %}
            {% include_relative snippets/correlations.md %}
            {% endcapture %}
            {% include modal-component.html title="Interactions between channels" content=correlations id="correlations" size="xl" %}
        </div>
    </div>
</div>
<br>

<!-- Pyvis interaction graph -->
<div class="graph-container mt-1">
    <iframe src="{{ '/assets/charts/Correlationcountries.html' | relative_url }}" width="100%" height="400px" frameborder="0" allowfullscreen></iframe>
</div>
 - In blue: Argentinian channels. In green: Italian channels

<!-- Section separator -->
<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

### to go further in our study we performed two analyses: sentiment and social network analysis
<br>
Keep reading our story by clicking the button below or going to **SENTIMENTS AND EMOTIONS** section in the navigation bar.

<div class="container mt-3">
    <div class="row justify-content-center">
        <div class="col-auto">
            <!-- Button to next section -->
            <a href="sentiment&emotion#Sentiments & Emotions" class="btn btn-primary">SENTIMENTS & EMOTIONS</a>
        </div>
    </div>
</div>