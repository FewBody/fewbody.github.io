---
title: "QFBD Research Group - Publications"
layout: gridlay
excerpt: "QFBD Research Group -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Group highlights

(For a full list of publications see [below](#full-list-of-publications) 

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>



## Full List of publications
<em>Junzhe Liu, Jin Lei, and Zhongzhou Ren</em><br /> Testing the validity of the surface approximation for reactions induced by weakly bound nuclei with a fully quantum-mechanical model <br /> <a href="https://doi.org/10.1103/PhysRevC.108.024606"> Phys. Rev. C 108, 024606 (2023)</a>
<em>Hao Liu, Shinsuke Nakayama, Jin Lei, and Zhongzhou Ren</em><br /> Comparison of Ichimura-Austern-Vincent and Glauber models for the deuteron-induced inclusive breakup reaction in light and medium-mass nuclei <br /> <a href="https://doi.org/10.1103/PhysRevC.108.014617"> Phys. Rev. C 108, 014617 (2023)</a>

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
