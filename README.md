# Dimensionality Reduction Methods and Relevant Applications to Galactic Images
A thesis presented in partial fulfillment of the requirements for the bachelor’s degree at Graduate School of Science, Nagoya University.
This repository contains a years worth of work during my undergraduate years as a member of the Laboratory of Galaxy Formation and Evolution at Nagoya University.

# Summary
This work builds upon the previous research into the use of PCA in simplifying the morphologies of galaxies into "eigengalaxies" in "Eigengalaxies: describing galaxy morphology using principal components in image space" (Uzeirbegovic et al., 2020).

We first replicate the work found in the above paper and explore the use of basic dimensionality reduction methods like PCA and NMF on galactic images and analyse the relationships found between the latent features of each galaxy's morphology with its physical properties.
We then expand upon this work by replacing the linear PCA/NMF models with non-linear ones like manifold learning (umap) and unsupervised learning networks (MLPs, CNNs, VAEs)
The latent features' relationships with the true physical properties are then analysed, and we propose several models for predicting such "uncaptured" properties of galaxies from just its appearance in an image.

# Abstract
We introduce the use of unsupervised neural networks in extracting features from galactic images, and demonstrate how such latent image features could be used as a simple method for estimating the physical properties of a galaxy in the absence of other data. As an illustrative example, we ran a dataset of 12539 \textit{i} band SDSS images through various types of unsupervised neural networks and showed that even with just 2 latent features, physical and morphological properties are distinctly clustered in latent space. We also compare the results of using unsupervised neural networks with methods explored by previous works, like Principal Component Analysis \citep{emir}.

# Presentation
Thesis slides can be found [here](https://docs.google.com/presentation/d/1-DFQQ-N4JdP7NaXe_vb9vtNrT7jw-HOG/edit#slide=id.p7) (English/Japanese)

# Conferences
The above work was shared at the following conferences/workshops:
- Poster presentation at the 9th East Asian Numerical Astrophysics Meeting held in Okinawa (September 26 - 30, 2022) [Poster here](https://drive.google.com/file/d/1p8KgDVcbgbj3gPB_b58x4WM6ZLkN1kal/view?usp=sharing)
- Short talk at the 4th Data Science in Astronomy Conference held at the Institute of Statistical Mathematics in Tokyo (October 3 - 5, 2022) [Slides here](https://docs.google.com/presentation/d/1eCxuSCMEshO7sUaviOSEWU8hxl2yHAMQ/edit?usp=sharing&ouid=106418298605170918085&rtpof=true&sd=true)
  
# Acknowledgements
I dedicate this work to my parents, without whose support I would never have been able to find my own way in life.
I also give thanks to my two close advisors: Professor Takeuchi Tsutomu and Dr. Suchetha Cooray, whose guidance have led to me developing a passion in the fields of ML and Data Science.
