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
  - title: Dr. Matthew Lungren
    time:
    url:
    image: assets/images/matthew_lungren.jpeg
    abstract:
    author:
      name: Dr. Matthew Lungren
      description: "Chief Medical Information Officer, Nuance Communications"
      bio: 
        "Dr. Lungren is Chief Medical Information Officer at Nuance Communications, a Microsoft Company. As a physician and clinical machine learning researcher, he maintains a part-time interventional radiology practice at UCSF while also serving as adjunct faculty for other leading academic medical centers including Stanford and Duke. 


        Prior to joining Microsoft, Dr Lungren was an interventional radiologist and research faculty at Stanford University Medical School where he led the Stanford Center for Artificial Intelligence in Medicine and Imaging (AIMI). More recently he served as Principal for Clinical AI/ML at Amazon Web Services in World Wide Public Sector Healthcare, focusing on business development for clinical machine learning technologies in the public cloud.


        His scientific work has led to more than 100 publications, including work on multi-modal data fusion models for healthcare applications, new computer vision and natural language processing approaches for healthcare specific domains, opportunistic screening with machine learning for public health applications, open medical data as public good, and prospective clinical trials for clinical AI translation. He has served as advisor for early stage startups and large fortune-500 companies on healthcare AI technology development and go-to-market strategy. Dr. Lungren is frequently featured in national news outlets such as NPR, Vice News, Scientific American, and he regularly speaks at national and international scientific meetings on the topic of AI in healthcare. 


        Dr. Lungren is also a top rated instructor on Coursera where his AI in Healthcare course designed especially for learners with non-technical backgrounds has been completed by more than 10k students around the world - enrollment is open now: [https://www.coursera.org/learn/fundamental-machine-learning-healthcare](https://www.coursera.org/learn/fundamental-machine-learning-healthcare)"
  - title: Dr. Gavriel State
    time:
    url:
    image: assets/images/Gavriel_State.jpeg
    abstract:
    author:
      name: Dr. Gavriel State
      description: "Senior Director for Simulation and AI at NVIDIA"
      bio:
        "Gavriel State is a Senior Director for Simulation and AI at NVIDIA, based in Toronto, where he leads efforts involving applications of AI technology to simulation systems and vice versa. This includes work on synthetic data generation through the [Omniverse Replicator system](https://developer.nvidia.com/nvidia-omniverse-platform/replicator), reinforcement learning and [sim-to-real robotics transfer](https://dextreme.org/) with [Isaac Gym](https://developer.nvidia.com/isaac-gym) and [Isaac Sim](https://developer.nvidia.com/isaac-sim), as well as supporting the development of 3D reconstruction technologies.


        Previously, Gavriel founded TransGaming Inc, and spent 15 years focused on real-time 3D rendering, pioneering the use of 3D API portability approaches for cross platform gaming with the WINE Windows compatibility environment, leading efforts to support WebGL in Google’s Chrome browser through ANGLE, and managing work on the SwiftShader software 3D renderer.
        

        Gavriel is a graduate of the University of Waterloo’s Systems Design Engineering program."
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
