---
title: "Explainable Bilevel Optimization: An Application to the Helsinki Deblur Challenge"
collection: publications
category: manuscripts
permalink: /publication/pezzi-2023-explainable-bilevel
#excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2023-01-01
venue: 'Inverse Problems and Imaging'
doi: 'https://doi.org/10.3934/ipi.2022055'
citation: 'S. Bonettini, G. Franchini, <strong>D. Pezzi</strong>, M. Prato, &quot;Explainable Bilevel Optimization: An Application to the Helsinki Deblur Challenge&quot;, in <i>Inverse Problems and Imaging</i>, 2023.'
---

In this paper we present a bilevel optimization scheme for the solution of a general image deblurring problem, in which a parametric variational like approach is encapsulated within a machine learning scheme to provide a high quality reconstructed image with automatically learned parameters. The ingredients of the variational lower level and the machine learning upper one are specifically chosen for the Helsinki Deblur Challenge 2021, in which sequences of letters are asked to be recovered from out-of-focus photographs with increasing levels of blur. Our proposed procedure for the reconstructed image consists in a fixed number of FISTA iterations applied to the minimization of an edge preserving and binarization enforcing regularized least-squares functional. The parameters defining the variational model and the optimization steps, which, unlike most deep learning approaches, all have a precise and interpretable meaning, are learned via either a similarity index or a support vector machine strategy. Numerical experiments on the test images provided by the challenge authors show significant gains with respect to a standard variational approach and performances comparable with those of some of the proposed deep learning based algorithms which require the optimization of millions of parameters.
