---
---

Welcome to RIIPL, a research group within the Atrium Wake Forest Baptist Health Department of Radiology. Our lab is dedicated to advancing the frontiers of medical imaging through the application of cutting-edge image analysis methods, including diffeomorphic registration, machine learning and AI development, graph theory analysis, and arterial spin labeling (ASL). At the heart of our mission is not just the development of these novel techniques, but their robust translation into clinical practice, improving patient care and outcomes.

Our team is comprised of a diverse group of experts—biomedical engineers, MR physicists, clinical radiologists, programmers—and a dynamic mix of students from various fields, all united by a shared passion for transforming healthcare. Our collaborative spirit extends beyond our lab, as we actively engage with a wide array of research groups, contributing our imaging expertise to studies in aging and dementia, radiation exposure, traumatic brain injury, and the health impacts of diet and exercise.

{%
  include button.html
  type="github"
  text="On GitHub"
  link="greenelab/lab-website-template"
%}
{%
  include button.html
  type="website"
  text="Official Website"
  link="https://school.wakehealth.edu/research/labs/radiology-informatics-and-image-processing-laboratory"
%}

{% include section.html %}

## Highlights
****
{% capture text %}

TODO: Here is for the intro to the list of our publications...

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
  image="images/riipl_logo_250.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

TODO: Here is the intro for the list of recent or interesting projects or Student work. 

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/riipl_logo_250_dark.png"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

TODO: Here is the place for the location of 

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
  image="images/riipl_logo_250_light.png"
  link="team"
  title="Our Team"
  text=text
%}
