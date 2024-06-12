---
styles:
  - message-wrap
---

## Message from Founder and Director

<div class="message-wrap">
  <figure class="image-wrap">
    <img src="images/staff_photos/chris_whitlow.jpg" alt="Dr. Christopher T. Whitlow" class="wrap-image">
    <figcaption>Dr. Christopher T. Whitlow, MD, PhD, MHA</figcaption>
  </figure>
  <blockquote class="content">
    <p>"Welcome to RIIPL, a research group within the Atrium Wake Forest Baptist Health Department of Radiology. Our lab is dedicated to advancing the frontiers of medical imaging through the application of cutting-edge image analysis methods, including diffeomorphic registration, machine learning and AI development, graph theory analysis, and arterial spin labeling (ASL). At the heart of our mission is not just the development of these novel techniques, but their robust translation into clinical practice, improving patient care and outcomes.</p>
    <p>Our team is comprised of a diverse group of experts—biomedical engineers, MR physicists, clinical radiologists, programmers—and a dynamic mix of students from various fields, all united by a shared passion for transforming healthcare. Our collaborative spirit extends beyond our lab, as we actively engage with a wide array of research groups, contributing our imaging expertise to studies in aging and dementia, radiation exposure, traumatic brain injury, and the health impacts of diet and exercise."</p>
  </blockquote>
</div>


{%
  include button.html
  type="github"
  text="On GitHub"
  link="The-Riipl-lab"
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

Our lab specializes in integrating cutting-edge neuroimaging analysis into studies of aging, diet, traumatic brain injury, and more. We pride ourselves on our extensive portfolio of recent publications, highlighting our ongoing contributions to various fields of research.

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
  image="images/riipl_logo_250_dark.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

From groundbreaking ongoing research projects to the exceptional work of our students and faculty. This space highlights our latest abstracts, posters, and speaking engagements, along with innovative software projects aimed at enriching the open-source community.

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
  image="images/riipl_logo_250.png"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Our Team is the cornerstone of our lab, comprising a vibrant mix of individuals from various disciplines united by a shared passion for neuroimaging research. Here, you can learn about each member's role, their specific research interests, and the unique contributions they bring to our collective pursuit of knowledge. Our lab thrives on the diversity of thoughts, skills, and interests each person contributes, making us a robust and dynamic force in the field.

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