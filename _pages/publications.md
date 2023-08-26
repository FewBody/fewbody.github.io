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

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>Systematic single-folding optical potential for 6Li and 7Li based on KD02 potentials</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/SF.png" class="img-responsive" width="40%" style="float: left" />
  <p>In the present research, we utilized the single-folding model to develop a systematical optical potential for 6Li and 7Li, employing the nucleon-nucleus global potentials introduced by Koning and Delaroche (KD02). We analyzed the elastic scattering angular distributions of 6Li and 7Li on targets with mass numbers ranging from 24 to 209 using the single-folding potential. Incident energies between 5 and 55 MeV/nucleon were considered. The real part of the single-folding model potential was renormalized with one free parameter, while leaving its imaginary part unchanged. The resulting renormalization factors of the single-folding model potentials show consistent systematics. Our approach effectively reproduced the elastic scattering and reaction cross sections of the targets in our current study. In addition, we also compared the prediction abilities of our systematic optical potentials with those of others.</p>
  <p><em>Yazhou Lu, Jin Lei, and Zhongzhou Ren</em></p>
  <p><strong><a href="https://doi.org/10.1103/PhysRevC.108.024612">Physical Review C 108, 024612 (2023)</a></strong></p>
 </div>
</div>

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>Testing the validity of the surface approximation for reactions induced by weakly bound nuclei with a fully quantum-mechanical model</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/medium.png" class="img-responsive" width="40%" style="float: left" />
  <p>We examine the validity of surface approximation for breakup reactions using a fully quantum-mechanical model proposed by Ichimura, Austern, and Vincent (IAV). Analogous to the semiclassical picture, we introduce radial cut-offs to scattering waves in the IAV framework, which we refer to as IAV-cut. Systematic calculations are conducted for nonelastic breakup reactions induced by 6Li and deuterons at various incident energies. A comparison between the results obtained from IAV and IAV-cut is performed. The excellent agreement observed between IAV and IAV-cut in 6Li induced reactions, regardless of incident energy and target nuclei, signifies their insensitivity to the inner part of the scattering wave function, thus providing validation for the semiclassical picture. However, for deuteron induced breakup reactions, the IAV-cut results exhibit a suppression in the cross section, suggesting a strong dependence on the interior wave functions. This suppression is further enhanced as the incident energy increases.</p>
  <p><em>Junzhe Liu, Jin Lei, and Zhongzhou Ren</em></p>
  <p><strong><a href="https://doi.org/10.1103/PhysRevC.108.024606">Physical Review C 108, 024606 (2023)</a></strong></p>
 </div>
</div>

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>Comparison of Ichimura-Austern-Vincent and Glauber models for the deuteron-induced inclusive breakup reaction in light and medium-mass nuclei </pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/second.png" class="img-responsive" width="40%" style="float: left" />
  <p>This study focuses on the deuteron-induced inclusive breakup reaction and investigates the (d,pX)and (d,nX) channels for light and medium mass nuclei. To study the double differential cross section of nonelastic breakup, we employed the models of Ichimura, Austern, and Vincent (IAV) [Phys. Rev. C 32, 431 (1985)] and the Glauber model with the quantum S matrix [Phys. Rev. C 80, 014604 (2009)], and compared the results for various reaction systems. Our analysis indicates that the Glauber model combined with the quantum S matrix yields good agreement with the IAV model in predicting the spectra of the deuteron-induced inclusive breakup cross section. Moreover, both models accurately predict the experimental data of light and medium mass targets. </p>
  <p><em>Hao Liu, Shinsuke Nakayama, Jin Lei, and Zhongzhou Ren</em></p>
  <p><strong><a href="https://doi.org/10.1103/PhysRevC.108.014617">Physical Review C 108, 014617 (2023)</a></strong></p>
 </div>
</div>
{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ Comparison of Ichimura-Austern-Vincent and Glauber models for the deuteron-induced inclusive breakup reaction in light and medium-mass nuclei }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/second.png" class="img-responsive" width="40%" style="float: left" />
  <p>{{This study focuses on the deuteron-induced inclusive breakup reaction and investigates the (d,pX)and (d,nX) channels for light and medium mass nuclei. To study the double differential cross section of nonelastic breakup, we employed the models of Ichimura, Austern, and Vincent (IAV) [Phys. Rev. C 32, 431 (1985)] and the Glauber model with the quantum S matrix [Phys. Rev. C 80, 014604 (2009)], and compared the results for various reaction systems. Our analysis indicates that the Glauber model combined with the quantum S matrix yields good agreement with the IAV model in predicting the spectra of the deuteron-induced inclusive breakup cross section. Moreover, both models accurately predict the experimental data of light and medium mass targets. }}</p>
  <p><em>{{Hao Liu, Shinsuke Nakayama, Jin Lei, and Zhongzhou Ren}}</em></p>
  <p><strong><a href="{{ https://doi.org/10.1103/PhysRevC.108.014617 }}">{{ Physical Review C 108, 014617 (2023) }}</a></strong></p>
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


<br />
<br />
## <br /> Full List of publications

<em>Yazhou Lu, Jin Lei, and Zhongzhou Ren</em><br /> Systematic single-folding optical potential for 6Li and 7Li based on KD02 potentials <br /> <a href="https://doi.org/10.1103/PhysRevC.108.024612"> Phys. Rev. C 108, 024612 (2023)</a>

<em>Junzhe Liu, Jin Lei, and Zhongzhou Ren</em><br /> Testing the validity of the surface approximation for reactions induced by weakly bound nuclei with a fully quantum-mechanical model <br /> <a href="https://doi.org/10.1103/PhysRevC.108.024606"> Phys. Rev. C 108, 024606 (2023)</a>

<em>Hao Liu, Shinsuke Nakayama, Jin Lei, and Zhongzhou Ren</em><br /> Comparison of Ichimura-Austern-Vincent and Glauber models for the deuteron-induced inclusive breakup reaction in light and medium-mass nuclei <br /> <a href="https://doi.org/10.1103/PhysRevC.108.014617"> Phys. Rev. C 108, 014617 (2023)</a>

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
