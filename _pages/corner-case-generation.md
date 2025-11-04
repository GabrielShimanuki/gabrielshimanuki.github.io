---
layout: single
classes: "wide"
author_profile: true
toc: false
toc_label: "Contents"
toc_icon: "cog"
# last_modified_at: 2024-12-03
permalink: /_pages/working_papers/corner-case-generation/
---

<!-- <style type="text/css">

body{ /* Normal  */
      font-size: 17px;
      text-align: justify;
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

/* Centralizando as figuras e ajustando o tamanho */
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
  max-width: 80%; /* Ajuste o tamanho da imagem */
}

figure {
  text-align: center;
}

/* Correção de fórmulas */
math, .math {
  font-size: 1.2em;
  text-align: center;
}

/* Ajustes específicos */
.page__content p small {
  font-size: 1em;
}

/* Centraliza as imagens e legendas */
.figure-align-center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  max-width: 55%; /* Ajuste a largura máxima conforme necessário */
}

.figcaption {
  text-align: center;
  font-size: 1em;
  color: #616161;
  font-style: italic;
  margin-top: 0.5em; /* Espaçamento acima da legenda */
}

.center-table {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.center-table table {
  width: auto; /* Adjusts the table width to its content */
}

.tabcaption {
  text-align: left;
  font-size: 1em;
  color: #616161;
  font-style: italic;
  margin-top: 0.5em; /* Espaçamento acima da legenda */
}

.content table {
  margin-left: auto;
  margin-right: auto;
  width: auto;
}

.no-margin {
  margin: 0 !important;
}

</style> -->

## Automated Generation of Corner Case Scenarios for Enhancing Autonomous Vehicle Safety

<strong>Abstract:</strong> Autonomous vehicles (AVs) must undergo extensive training and testing to ensure safety in diverse and unpredictable environments. Despite advancements in data collection and simulation, traditional datasets often fail to capture rare yet critical corner case scenarios, where system failures could result in severe consequences. This paper presents a novel approach to address this gap through an automated framework that identifies, generates, and evaluates high-risk scenarios.

<strong>Brief Explanation:</strong> Corner case scenarios—highly unusual but safety-critical situations—are essential for validating AV control systems. Conventional data collection methods, including real-world testing and basic simulations, fall short in addressing these rare conditions. This paper proposes a robust framework that integrates advanced simulation tools and optimization techniques to generate synthetic datasets designed to expose AV systems to diverse, challenging, and safety-critical situations.

The proposed framework combines CARLA, a high-fidelity traffic simulator, with Scenic, a scenario description language, to create highly customizable and complex traffic scenarios. Parameters such as traffic density, vehicle dynamics, and environmental factors are iteratively refined using a Genetic Algorithm (GA). The GA optimizes these scenarios based on metrics such as Time-to-Collision (TTC) and minimum stopping distances, ensuring a focus on high-risk conditions. Custom heuristics complement the risk metrics to identify scenarios that represent realistic and challenging operational environments.

The synthetic datasets produced by this framework provide a scalable and efficient solution for testing AV systems under critical conditions. By exposing control algorithms to a wider variety of corner cases, this research improves the robustness and reliability of AV systems, reducing the likelihood of real-world failures and accidents. This work addresses a significant gap in the field and sets the stage for safer autonomous systems through enhanced testing methodologies.

By automating the generation of corner case scenarios, this framework advances the capabilities of AV training and validation. It highlights the importance of scalable, high-fidelity data generation methods to ensure the safety and reliability of AV systems in real-world scenarios. This paper contributes to ongoing efforts in making autonomous systems safer and more dependable for widespread adoption.