---
title: Home
---

# So Lab

Hi! Thanks for stopping by!

We are a bioinformatics research lab at The Chinese University of Hong Kong, [The School of Biomedical Sciences](https://www2.sbs.cuhk.edu.hk/). Our lab is led by [Prof. SO Hon-Cheong](https://www2.sbs.cuhk.edu.hk/en-gb/people/academic-staff/prof-so-hon-cheong), and we focus on genomics and drug discovery research.

This website is built based on Greene Lab's lab website [template](https://greenelab.github.io/lab-website-template/). Our modification of the template is documented [here](https://github.com/Carlos-Chau/so-lab).

<!-- section break -->

# Highlights

{% capture text %}
Research Highlights

[Publication &nbsp;→](research)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/genome-map.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
Our Team

[Our team &nbsp;→](team)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/marvin-meyer-SYTO3xs06fU-unsplash.jpg"
  link="team"
  title="Our Team"
  text=text
%}
