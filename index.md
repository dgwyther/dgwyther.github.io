---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
{::nomarkdown}
<p align="center">
<img src="{{site.baseurl}}Profile_Pic.jpg" width="30%" height="30%"/>
</p>
<p align="center">
Ice/Ocean/Climate Research Scientist  |  Brisbane, Queensland, Australia
</p>
{:/}
------

## Professional Profile
* **Postdoctoral research associate** at the University of Tasmania, Antarctic Gateway Partnership, where I research ocean-ice shelf interaction using numerical models.
* **Fulbright scholar** (2013-2014; University of Texas, Austin).
* **High impact publications**: First-author publication in Nature Communications showing impact of natural variability on the cryosphere. 
* **Multidisciplinary experience**: Ice shelf-ocean interaction, oceanography, glaciology, climate dynamics and variability, air-sea interaction, computational physics, frequency analysis, ecosystem modelling, statistics
* **High publication outputs**: 13 journal articles, 10 conference proceedings and 10 media and public engagement articles (as of March 2020). 
* **Innovative and collaborative**: Lead UTas component of major international project; lead CI on 4 major competitive grants; published with 49 co-authors from 31 different institutes across 9 countries.
* **Field scientist**: senior field scientist on a 3-month Autonomous Underwater Vehicle mission to Antarctica (2018/2019); oceanographer on a 2-month voyage to East Antarctica (2014).

* * *

## News
{%- if site.posts.size > 0 -%}
{% for post in site.posts %}
   - {{ post.date | date_to_string }} - [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
{%- endif -%}


