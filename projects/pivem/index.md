---
layout: nodesig
---
## <center>Piecewise-Velocity Model for Learning Continuous-time Dynamic Node Representations</center>
### Motivation
<h5 align="justify">
We propose the <b>Pi</b>ecewise-<b>Ve</b>locity <b>M</b>odel (<b>PiVeM</b>) for the representation of continuous-time dynamic networks. It learns dynamic embeddings in which the temporal evolution of nodes is approximated by piecewise linear interpolations based on a latent distance model with piecewise constant node-specific velocities. The model allows for analytically tractable expressions of the associated Poisson process likelihood with scalable inference invariant to the number of events. We further impose a scalable Kronecker structured Gaussian Process prior to the dynamics accounting for community structure, temporal smoothness, and disentangled (uncorrelated) latent embedding dimensions optimally learned to characterize the network dynamics. We show that <b>PiVeM</b> can successfully represent network structure and dynamics in ultra-low two and three-dimensional embedding spaces. We further extensively evaluate the performance of the approach on various networks of different types and sizes and find that it outperforms existing relevant state-of-art methods in downstream tasks such as link prediction. In summary, <b>PiVeM</b> enables easily interpretable dynamic network visualizations and characterizations that can further improve our understanding of the intrinsic dynamics of time-evolving networks.
</h5>

<h2><center>This page will be updated soon.</center></h2>




### Code
##### An implementation of the project in C++ can be reached at the [Github](https://github.com/abdcelikkanat/pivem) repository.

### Contributors
##### [Abdulkadir Çelikkanat](http://abdcelikkanat.github.io/), [Nikolaos Nakis](https://github.com/Nicknakis) and [Morten Mørup](http://www.mortenmorup.dk/)

### References
##### A. Celikkanat, N. Nakis and M. Mørup, [Piecewise-Velocity Model for Learning Continuous-time Dynamic Node Representations](.), Proceedings of the First Learning on Graphs Conference (LoG 2022), PMLR 198, Virtual Event, December 9–12, 2022.
