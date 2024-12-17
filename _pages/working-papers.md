---
layout: single
author_profile: true
toc: false
toc_label: "Contents"
toc_icon: "cog"
last_modified_at: 2024-12-03
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


## Adaptive Bayesian Filtering in Action

![FPGA Image](/assets/images/fpga_image.png){: .small-image}

This project focuses on implementing an adaptive Bayesian filter on an FPGA to enhance the accuracy of low-cost sensors, specifically the HC-SR04 ultrasonic sensor. The filter, based on Bayesian networks, is developed using VHDL and processes floating-point data. Experimental results demonstrate improvements in the variance of the filtered measurements compared to the raw readings, although optimizing the filter parameters remains a challenge. The project validates the model's functionality and suggests that large-scale testing could be a valuable direction for future research. [Read More](/_pages/working_papers/adaptive-bayesian-filter/){: .btn .btn--primary .no-margin}
