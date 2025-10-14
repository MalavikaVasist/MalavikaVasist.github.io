---
layout: default
title: Masters project
description: 
---

<h2>Masters</h2>

Here are some of my projects:

<div class="content">
<div class="link">
  <a href="{{ '/assets/pdfs/FirstyearThesis.pdf' | relative_url }}" target="_blank" class="link">
    <h3>The relation between galaxy morphology and merger history in EAGLE simulations</h3>
  </a>
</div>

<figure>
  <img src="/assets/images/Eagle.png" alt="EAGLE simulations" width="350" height="250">
  <figcaption></figcaption>
</figure>

For my first masters thesis, I investigated the link between merger history of galaxies, stellar mass, and galaxy morphology using the EAGLE cosmological hydrodynamical simulations. Stellar mass of a galaxy was defined as the total stellar mass within 30kpc. Galaxy morphology was quantified using a kinematic based parameter called kappa-corotating, and the distribution of ellipticals and disks across redshifts in the simulation was mapped. Galaxy pairs within a certain spatial proximity were considered to be impending merger events, and they were differentiated as either major or minor, depending on the ratio of the masses of the galaxies comprising it. The contribution of major mergers in the evolution of galaxies was estimated by the fraction of galaxies in close pairs, namely the fraction of major mergers (fMM). fMM revealed that the probability of major mergers was independent of stellar mass but depends on morphology, with fMM being higher for ellipticals than disks at all redshifts, agreeing with observational estimates. The study also revealed that independent of morphology, the probability of mergers increased with the increase in redshift. To understand the morphological composition of galaxies in close pairs, the fraction of the pairs constituting galaxies belonging to the same morphology were calculated. It was found that the probability of finding two elliptical galaxies merging was higher than finding two disk type galaxies.
</div>

<div class = "content">
<div class="link">
  <a href="{{ '/assets/pdfs/SecondyearThesis.pdf' | relative_url }}" target="_blank" class="link">
    <h3>Using Deep Learning to predict the properties of galaxy major mergers in EAGLE simulations</h3>
  </a>
</div>

<figure>
  <img src="/assets/images/galaxy-merger.jpg" alt="Galaxy merger" width="350" height="250">
  <figcaption></figcaption>
</figure>

For my second masters thesis, I used the mergers I had identified in my first masters thesis to infer merger properties by training a deep neural network. The  galaxy merger images were generated from EAGLE simulations with their corresponding labels of their size and mass ratio. Two image sets of data were generated for galaxy mergers, at redshift z=0 and 20$>$z$>$0 separately, using two zooming techniques, one from the EAGLE package and the second was a self written zooming algorithm. The training resulted in mass ratio accuracies of 85\% and 80\% and a 90\% and 70\% on their size ratios respectively in each of the datasets. Similar accuracies in either case implied that the visualization techniques aren’t crucial to the training, suggesting that the model was robust. The high accuracies achieved using deep neural networks suggested that they are effective tools in studying galaxy mergers. Further, the study concluded that the accuracies can be improved by increasing the resolution of the images. Hence making it a useful tool to study observational images of galaxy mergers. This experience enriched my practical skills in training, evaluating, and testing neural networks, utilizing platforms like Keras and TensorFlow.
</div>

<div class = "content">
<div class="link">
  <a href="{{ '/assets/pdfs/NN_project.pdf' | relative_url }}" target="_blank" class="link">
    <h3>Predicting the Impact of Perturbers on Planetary Systems in Star Clusters</h3>
  </a>
</div>

I also worked on a project to investigate start clusters using deep learning. Star clusters are considered to be a chaotic environment for planet formation, since they are very densely packed with stars. A close encounter with a perturber, such as a star passing by, can cause the orbital parameters of the planetary system to be excited to such an extent that a planet is ejected from the system. In order to simulate planet formation in star clusters, N-body simulations are used. These simulations are computationally expensive and take a long time to perform. As an alternative, I worked on using a neural network to replace part of the simulation and predict parameter evolution. We found mixed results for our models, but predicted that this method can be successful with more training data and further hyper parameter tuning.
</div>
