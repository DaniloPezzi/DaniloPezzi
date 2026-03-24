---
title: "Learning the Image Prior by Unrolling an Optimization Method"
collection: publications
category: manuscripts
permalink: /publication/pezzi-2022-learning-the-image
#excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2022-01-01
venue: '2022 30th European Signal Processing Conference (EUSIPCO)'
doi: https://doi.org/10.23919/EUSIPCO55093.2022.9909852
citation: 'S. Bonettini, G. Franchini, <strong>D. Pezzi</strong>, M. Prato, &quot;Learning the Image Prior by Unrolling an Optimization Method&quot;, in <i>2022 30th European Signal Processing Conference (EUSIPCO)</i>, 2022.'
---

Nowadays neural networks are omnipresent thanks to the amazing adaptability they possess, despite their poor interpretability and the difficulties they give when manipulating the parameters. On the other side, we have the classical variational approach, where the restoration is obtained as the solution of a given optimization problem. The bilevel approach
is connected to both approaches and consists first in devising a parametric formulation of the variational problem, then in
optimizing these parameters with respect to a given dataset of training data. In this work we analyze the classical bilevel
approach in combination with unrolling techniques, where the parameters of the variational problem are trained with respect
to the results obtained after a fixed number of iterations of an optimization method applied to it. This results in a large
scale optimization problem which can be solved by means of stochastic methods; as we observed in our numerical experiments,
the stochastic approach can produce medium accuracy results in very few epochs. Moreover, our experiments also show that the
unrolling approach leads to results which are comparable with those of the original bilevel method in terms of accuracy.
