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
  - title: Post deployment considerations for AI in Radiology
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
  - title: Synthetic Data for Computer Vision and Agile Robotic Manipulation
    time:
    url:
    image: assets/images/Gavriel_State.jpeg
    abstract:
    author:
      name: Gavriel State
      description: "Senior Director for Simulation and AI at NVIDIA"
      bio:
        "Gavriel State is a Senior Director for Simulation and AI at NVIDIA, based in Toronto, where he leads efforts involving applications of AI technology to simulation systems and vice versa. This includes work on synthetic data generation through the [Omniverse Replicator system](https://developer.nvidia.com/nvidia-omniverse-platform/replicator), reinforcement learning and [sim-to-real robotics transfer](https://dextreme.org/) with [Isaac Gym](https://developer.nvidia.com/isaac-gym) and [Isaac Sim](https://developer.nvidia.com/isaac-sim), as well as supporting the development of 3D reconstruction technologies.


        Previously, Gavriel founded TransGaming Inc, and spent 15 years focused on real-time 3D rendering, pioneering the use of 3D API portability approaches for cross platform gaming with the WINE Windows compatibility environment, leading efforts to support WebGL in Google’s Chrome browser through ANGLE, and managing work on the SwiftShader software 3D renderer.
        

        Gavriel is a graduate of the University of Waterloo’s Systems Design Engineering program."
  - title: Physical Knowledge-Informed Learning Adaptation for Internet-of-Things
    time:
    url: 
    image: assets/images/pan_shijia_190925-1_1.jpg
    abstract: "The number of everyday Internet-of-Things (IoT) devices is projected to grow to the billions in the coming decade, which enables various smart building applications. These applications, especially in-home long-term occupant monitoring, rely on the emerging non-intrusive sensing techniques. The acquired IoT sensing data are often of varying data efficiency/quality due to the system and/or deployment constraints, and sensing data distributions can change significantly under different sensing conditions. Therefore, from the data/learning perspective, accurate information learning through pure data-driven approaches requires a large amount of labeled data, which is costly and difficult to obtain in real-world applications. We address these challenges by combining physical and data-driven knowledge to reduce label data needed via physical knowledge-guided model transfer. In this talk, we use structural vibration-based occupant sensing applications to evaluate our model transfer schemes."
    author:
      name: Dr. Shijia Pan
      description: University of California Merced
      bio:
        "Dr. Shijia Pan is an Assistant Professor at the University of California Merced. She received her bachelor’s degree in Computer Science and Technology from the University of Science and Technology of China and her Ph.D. degree in Electrical and Computer Engineering from Carnegie Mellon University. Her research interests include cyber-physical sensing systems (CPS), multimodal learning for CPS/IoT, and ubiquitous computing. She worked in multiple disciplines and focused on indoor human information acquisition through ambient sensing. She has published in both top-tier Computer Science ACM/IEEE conferences and high-impact Civil Engineering journals. She received Rising Stars in EECS, Nick G. Vlahakis Graduate Fellowship, Google Anita Borg Scholarship, Best Paper Awards (IoTDI, ASME SHM/NDE, HASCA), Best Poster Awards (SenSys, IPSN), Best Demo Award (Ubicomp, BuildSys), Best Presentation Award (SenSys Doctoral Colloquium), and Audience Choice Award (BuildSys) from ACM/IEEE conferences."
  - title: Combine remote sensing and machine learning in support of digital agriculture
    time: 
    url: 
    image: https://digitalag.bse.wisc.edu/wp-content/uploads/sites/1003/2019/03/Zhang-3-300x300.png
    abstract: 
      "
      Maintaining and improving the productivity and resiliency of our agricultural and food systems, while simultaneously mitigating and adapting to climate change in the face of an uncertain future and increasingly competitive uses of limited resources, represents a grand challenge of our time. My research, as an interdisciplinary study, endeavors to address this challenge by combining advanced sensing systems with computational engineering technologies. In this presentation, I will introduce our lab’s recent accomplishments and ongoing research work include 1) Combining satellite remote sensing with deep learning/machine learning for large-scale crop monitoring and management decision making; 2) Combining unmanned aerial vehicles (UAVs) based high-resolution images with deep learning/machine learning for fine-scale high-throughput plant phenotyping and other precision agricultural applications; and 3) Cyber-infrastructure tools development for agricultural decision making. 
      "
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

{% if keynote.abstract %}
**Abstract:** 
{{keynote.abstract}}
{% endif %}

**Speaker Info:**
{{keynote.author.name}}

{{keynote.author.description}}

{{keynote.author.bio}}

{% endfor %}
