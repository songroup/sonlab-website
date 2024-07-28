---
---

<!-- # Son Research Lab -->

<style>
  iframe {
    width: 100%;
    height: min(400px, 50vw);
    border: none;
  }
</style>
  
<iframe src="map"></iframe>

\\
Our lab is a collective of molecular simulation research investigators with an interest in studying the energy/bio soft materials system. Molecular simulation is performed to quantitatively analyze the structure, dynamics, thermodynamics and reaction kinetics of several systems from the physical models given. Our mission is not only to provide the microscopic understanding of various molecular-level phenomena, but also to develop the advanced computational techniques / algorithms to properly capture the underlying physics and enhance the predictive power of molecular simulation. We have strong expertise in running molecular dynamics simulation, as well as high-performance supercomputing ecosystem equipped with ~150 GPUs for highly efficient computation. We have formed a strong network of research and experimental collaborations to pursue innovative studies in computational chemistry research.

<!--
{%
  include figure.html
  image="images/Research.png"
  width="1000px"
%}
-->

{% include section.html full=true %}

{% capture text %}

We are computational chemistry lab at SNU Department of Chemistry.

Our lab develops molecular simulations to solve problems that are critical in energy / bio applications. We use & develop statistical mechanics / molecular dynamics / coarse-grained methods / machine-learning / big data analysis to understand the mechanisms of chemical processes and help designing new functional materials.

{%
  include button.html
  link="publications"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}


{%
  include feature.html
  image="images/landscape.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

We are a group of graduate students and post-docs with a passion for running molecular simulations and advancing computational algorithms. We are looking for motivated individuals with a passion for computational chemistry research. If you're interested, please consider joining us.
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
  width="600px"
%}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-feather-pointed" %}News

{% include list.html data="posts" component="post-excerpt" %}

