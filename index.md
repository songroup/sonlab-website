---
---

{% include section.html %}

{% capture text %}

We are computational chemistry lab at SNU Department of Chemistry.

Our lab develops molecular simulations to solve problems that are critical in energy/bio applications. We use/develop statistical mechanics / molecular dynamics / coarse-grained methods / machine-learning / big data analysis to understand the mechanisms of chemical processes and help designing new functional materials.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Research.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

We're a group of graduate students, data scientists, and software engineers with a passion for applied computing and advancing cancer research. We are looking for motivated individuals with a passion for data science and cancer research. If you're interested, [please consider joining us](/join-us).

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/group_photo.jpeg"
  link="team"
  title="Our Team"
  text=text
%}
