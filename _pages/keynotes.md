---
title: Keynotes
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: https://cvis2021.weebly.com/uploads/5/6/3/0/56308869/background-images/236520036.jpg
  actions:
permalink: /keynotes
toc: true
keynotes:
  - title: Dr. Zhou Zhang
    time: 
    url: 
    image: https://digitalag.bse.wisc.edu/wp-content/uploads/sites/1003/2019/03/Zhang-3-300x300.png
    abstract: 
    author:
      name: Dr. Zhou Zhang
      description:
        "Assistant Professor, University of Wisconsin-Madison, USA"
      bio:
        "Dr. Zhou Zhang received her B.S degree in astronautics engineering and M.S. degree in instrumentation science and opto-electronics engineering from Beihang University, Beijing, China, in 2010 and 2013, respectively. Then, she got her Ph.D. degree in 2017 in geomatics, civil engineering at Purdue University, USA. Her dissertation topic is about developing new machine learning methods for hyperspectral remote sensing data classification. During 2017-2019, she worked as a Postdoc Scholar at the University of California, Davis on almond yield prediction using satellite remote sensing (Landsat and others) and machine learning.

        She is currently an Assistant Professor in Biological Systems Engineering in College of Agriculture and Life Science at the University of Wisconsin-Madison, USA. Her research interests include satellite remote sensing (Landsat, MODIS, Sentinel, etc), drone-based imaging platform developments for precision agriculture, multi-source remote sensing data fusion, artificial intelligence and machine learning in agricultural applications. Dr. Zhang has over 40 publications in peer-reviewed journals and conferences. Dr. Zhang was a recipient of the Best Student Paper (third place) in 2016 IEEE IGARSS Student Paper Competition. For more details, please visit Dr. Zhang’s lab website [https://digitalag.bse.wisc.edu](https://digitalag.bse.wisc.edu)"
---


{% for keynote in page.keynotes %}
## {{ keynote.title }}
<img src="{{ keynote.image}}" class="align-left" style="width: calc(30% - 0.5em);"/>

{% if keynote.time %} <sub>{{keynote.time}} </sub>  {% endif %}


{% if keynote.url %} <sub> {{keynote.url}}</sub> {% endif %}

{% if keynoe.abstract %}
**Abstract:** 
{{keynote.abstract}}
{% endif %}

**Speaker Info:**
{{keynote.author.name}}

{{keynote.author.description}}

{{keynote.author.bio}}

{% endfor %}
