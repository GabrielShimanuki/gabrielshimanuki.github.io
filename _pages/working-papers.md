---
layout: single
author_profile: true
toc: false
toc_label: "Contents"
toc_icon: "cog"
# last_modified_at: 2024-12-03
---
<style type="text/css">

body{ /* Normal  */
      font-size: 17px;
  }

.author__avatar{
    padding-left:10%;
    padding-right:10%;
}

.author__name{
    /* margin-bottom: 20px; Adjust space after name */
    text-align: center;
}

.author__content{
    text-align: center;

}

.author__avatar img{
    max-width:100%;
}

.author__urls{
    padding-left: 15%;
}

.page__content p {
    margin-top: 1.5em;
    margin-bottom: 1.5em;
}

.page{
    padding-right: 0%;
    font-size: 15px;
}

strong {
    color: #616161;
}

.justify-text {
  text-align: justify;
}

.fa-rss {
  display: none;
}

.footer .fa-rss {
  display: none !important;
}

a[href="/feed.xml"] {
  display: none;
}

.small-image {
  width: 250px; /* Adjust the size as needed */
  height: auto; /* Maintain aspect ratio */
  float: left; /* Align to the left */
  margin-right: 1rem; /* Add spacing between image and text */
}

</style>


<!-- ## Adaptive Bayesian Filtering in Action -->
## Bayesian Filtering on FPGA: Enhancing Low-Cost Ultrasonic Sensor Reliability for Distance Measurement

![FPGA Image](/assets/images/fpga_image.png){: .small-image}

<div class="justify-text">
This project focuses on implementing an adaptive Bayesian filter on an FPGA to enhance the accuracy of low-cost sensors, specifically the HC-SR04 ultrasonic sensor. The filter, based on Bayesian networks, is developed using VHDL and processes floating-point data. Experimental results demonstrate improvements in the variance of the filtered measurements compared to the raw readings, although optimizing the filter parameters remains a challenge. The project validates the model's functionality and suggests that large-scale testing could be a valuable direction for future research. [Read More](/_pages/working_papers/adaptive-bayesian-filter/){: .btn .btn--primary .no-margin}
</div>

<!-- ## Systematic Literature Review of Corner Case Identification and Generation -->
## Automating Corner Case Generation in Traffic Scenarios: A Systematic Literature Review

![Corner Case SLR](/assets/images/SLR/CC_cover.png){: .small-image}

<div class="justify-text">
This systematic literature review investigates the critical role of corner case identification and generation in autonomous vehicle (AV) testing, aiming to bridge gaps in safety and robustness research. By analyzing state-of-the-art methodologies, this review highlights the importance of corner cases in evaluating AV systems' ability to handle rare but high-risk scenarios. It also addresses the limitations of previous studies, such as outdated coverage, insufficient focus on generation methods, and reproducibility challenges. This brief work provides a comprehensive overview of the advancements, regional trends, and future directions in this field. [Read More](/_pages/working_papers/slr-corner-case/){: .btn .btn--primary .no-margin}
</div>

<div style="display: flex; gap: 1rem; margin-top: -55px; margin-bottom: -40px;">
<small>Image source: <a href="https://medium.com/anyverse/detecting-corner-cases-for-visual-perception-in-autonomous-driving-82580ef373ac" target="_blank">Medium</a></small>
</div>

<!-- ## Automated Generation of Corner Case Scenarios for Enhancing Autonomous Vehicle Safety -->
## Genetic Algorithm-Driven Corner Case Generation: Advancing Simulation for Safer Autonomous Vehicle Systems

![Corner Case Generation](/assets/images/CC_GENERATION/CARLA_cover.png){: .small-image}

<div class="justify-text">
This project aims to advance the safety of autonomous vehicles (AVs) by developing an automated framework to generate and evaluate critical corner case scenarios. These scenarios, which expose AV systems to rare and high-risk situations, are essential for ensuring the reliability of AV control algorithms. By integrating CARLA and Scenic, a robust simulation environment is created to define complex traffic conditions. A Genetic Algorithm (GA) refines these scenarios iteratively, guided by risk metrics and customized heuristics. This framework generates high-fidelity datasets that enhance AV training and testing, improving their ability to handle real-world challenges. [Read More](/_pages/working_papers/corner-case-generation/){: .btn .btn--primary .no-margin}
</div>

<div style="display: flex; gap: 1rem; margin-top: -55px; margin-bottom: -40px;">
<small>Image source: <a href="https://carla.readthedocs.io/en/0.9.15/catalogue_vehicles/" target="_blank">CARLA</a></small>
</div>

## Making Even More with Much Less: Improving Software Testing Outcomes Using a Cross-Project and Cross-Language ML Classifier Based on Cost-Sensitive Training on Class-Weighted Dataset

![Corner Case Generation](/assets/images/SOFTWARE_TESTING/software_testing_cover.png){: .small-image} 

<div class="justify-text">
TBD
</div>

<div style="display: flex; gap: 1rem; margin-top: -55px; margin-bottom: -40px;">
<small>Image source: <a href="https://initialcommit.com/blog/how-to-be-a-software-developer" target="_blank">Blog</a></small>
</div>