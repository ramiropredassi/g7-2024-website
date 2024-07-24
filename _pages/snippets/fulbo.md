
# Fernanditos Team - Passionate football fans

**We are an interdisciplinary and heterogeneous group with different backgrounds and trajectories but a common passion: football!**

<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

### Do you want to know a little more about us?

Our team is made up of five football fanatics!  

<div class="container">
    {% for people in site.data.team %}
        <div class="row py-2 justify-content-left">
            <div class="col-2">
                <img src="{{ people.url_img }}" alt="{{ people.alt }}" style="vertical-align: middle;">
            </div>
            <div class="col-10">
                <p> <strong>{{ people.name }}</strong><br>{{ people.description }}</p>
            </div>
        </div>
    {% endfor %}
</div>

<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

### Driven to understand if our friendship story was unique, we found it interesting **to explore whether football is an element of union or division.** 

Moved to nourish our understanding, we found something amazing: two concepts are associated with this issue in the literature!
  - Ingroup **[intergroup]**
  - Outgroup **[‘outside the group’](#footnote)**


>We saw that these two concepts have something in common: <br>**_IT IS ALL ABOUT GROUPS!_**
><br>Despite being fans of different football clubs we are not lonely watchers: **_Groups, or communities, are what ties everything together!_**

<div id="footnote">
  <strong></strong>
    White, F. A., Newson, M., Verrelli, S., & Whitehouse, H. (2021). Pathways to prejudice and outgroup hostility: Group alignment and intergroup conflict among football fans. *Journal of Applied Social Psychology, 51*(7), 660–666. https://doi.org/10.1111/jasp.12773; Newson, M., White, F. & Whitehouse, H. (2023). Does loving a group mean hating its rivals? Exploring the relationship between ingroup cohesion and outgroup hostility among soccer fans. *International Journal of Sport and Exercise Psychology, 21*(4), 706-724, DOI: 10.1080/1612197X.2022.2084140
</div>
<style>
  #footnote {
    border-top: 1px solid #ccc;
    margin-top: 20px;
    padding-top: 10px;
    font-size: 0.9em;
    line-height: 1.4;
  }

  #footnote strong {
    display: block;
    margin-bottom: 10px;
  }
</style>

<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

## Why football? Besides our passion for this sport, this is also the most popular sport today!
With its 5 billion fans around the world (FIFA 2021), football has become a true social phenomenon that can be studied from different points of view. This discipline can also analyse different aspects of society.

Even if we want to explore what happens in each club, country, and continent, limiting our initial search to two cases, Italy 🇮🇹 and Argentina 🇦🇷, is pertinent.
<br>Not only do we love ❤️ these countries' football clubs, but they are nations that share a common history despite being separated by the ocean. 

<!-- Button to see historical connections between italy and Argentina -->
<div class="container mt-3">
    <div class="row justify-content-center">
        <div class="col-auto">
            {% capture whyArgIT %}
            {% include_relative snippets/whyArgIT.md %}
            {% endcapture %}
            {% include modal-component.html title="Why Italy and Argentina" content=whyArgIT id="whyArgIT" size="xl" %}
        </div>
    </div>
</div>

<br>Italians and Argentinians are passionate about football 
Both countries also share common historical roots, and there are numerous examples of players who connect both football realities!.

<!-- Section separator -->
<div class="d-flex align-items-center my-4">
  <hr class="flex-grow-1">
  <img src="{{ '/assets/images/separator.png' | relative_url }}" alt="Football" style="width: 110px; height: 50px; margin: 0 10px;">
  <hr class="flex-grow-1">
</div>

### To find out everything we discovered, keep reading our story.
<br>

