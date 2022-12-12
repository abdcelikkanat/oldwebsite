---
layout: pivem
---
## <center>Piecewise-Velocity Model for Learning Continuous-time Dynamic Node Representations</center>
### Motivation
<h5 align="justify">
We propose the <b>Pi</b>ecewise-<b>Ve</b>locity <b>M</b>odel (<b>PiVeM</b>) for the representation of continuous-time dynamic networks. It learns dynamic embeddings in which the temporal evolution of nodes is approximated by piecewise linear interpolations based on a latent distance model with piecewise constant node-specific velocities. We show that <b>PiVeM</b> can successfully represent network structure and dynamics in ultra-low two and three-dimensional embedding spaces. We further extensively evaluate the performance of the approach on various networks of different types and sizes and find that it outperforms existing relevant state-of-art methods in downstream tasks such as link prediction. In summary, <b>PiVeM</b> enables easily interpretable dynamic network visualizations and characterizations that can further improve our understanding of the intrinsic dynamics of time-evolving networks.
</h5>

<div style="margin: 30px 0px;">
<center>
<div style="width:50%; float: left;">
<video width="100%;" controls>
<source src="/assets/pivem/synthetic_pi_ground_truth.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
<h5 style="margin:0px; padding:0px;">Ground Truth</h5>
</div>
<div style="width:50%; float: left;">
<video width="100%" controls>
<source src="/assets/pivem/synthetic_pi_learned_model.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
<h5 style="margin:0px; padding:0px;">Learned Model</h5>
</div>
<h4 style="margin:0px; padding:0px; font-weight: bold;">Comparisons of the ground truth and learned representations in two-dimensional space for the Synthetic(π) symbol.</h4>
</center>
</div>

### Code
##### An implementation of the project in C++ can be reached at the [Github](https://github.com/abdcelikkanat/pivem) repository.

### Contributors
##### [Abdulkadir Çelikkanat](http://abdcelikkanat.github.io/), [Nikolaos Nakis](https://github.com/Nicknakis) and [Morten Mørup](http://www.mortenmorup.dk/)

### References
##### A. Celikkanat, N. Nakis and M. Mørup, [Piecewise-Velocity Model for Learning Continuous-time Dynamic Node Representations](.), Proceedings of the First Learning on Graphs Conference (LoG 2022), PMLR 198, Virtual Event, December 9–12, 2022.
