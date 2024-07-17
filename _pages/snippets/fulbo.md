
# Fernanditos Team - Passionate football fans

**We are an interdisciplinary and heterogeneous group with different backgrounds and trajectories but a common passion: football!**

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

# Why We Have Chosen Football as Our Theme

**Football is the most popular sport in the world, with 5 billion fans according to FIFA (2021).**

Through football, various topics are studied such as politics, culture, economics, psychology, tourism, and more. Football allows the examination of multiple aspects of society, such as inclusion, brotherhood, and team spirit (Halldorsson 2018), but also division, rivalry, and violence (Newson 2019).

# Why the Comparison Between Italy and Argentina?

It is estimated that between 1870 and 1960, over 2 million Italian citizens moved to Argentina. Many Argentine politicians, actors, models, and several sports figures have Italian origins. River Plate, one of the most representative teams in Argentina alongside Boca Juniors, owes its origin to a group of Genoese boys who arrived in Buenos Aires seeking fortune.

# Final Analysis of our work

In our search for the discovery of communities inside the social network Twitch, channels of Twitch where the main topic is Football, we have chosen to analyze both Italy and Argentina due to the cultural and historical relation between the two nations and their known passion for football. This took our project to work with both languages Italian and Spanish to look for insight in our data.