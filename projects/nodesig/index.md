---
layout: nodesig
---
## <center>NodeSig: Binary Node Embeddings via Random Walk Diffusion</center>
### Motivation
<h5 align="justify">
As the scale of networks increases, most of the widely used learning-based graph representation models also face computational challenges. While there is a recent effort toward designing algorithms that solely deal with scalability issues, most of them behave poorly in terms of accuracy on downstream tasks. In this paper, we aim to study models that balance the trade-off between efficiency and accuracy. In particular, we propose \textsc{\modelabbrv}, a  scalable model that computes binary node representations. \textsc{\modelabbrv} exploits random walk diffusion probabilities via stable random projections towards efficiently computing embeddings in the Hamming space. Our extensive experimental evaluation on various networks has demonstrated that the proposed model achieves a good balance between accuracy and efficiency compared to well-known baseline models on the node classification and link prediction tasks.
</h5>


<style>
/* Three image containers (use 25% for four, and 50% for two, etc) */
.column {
  ;
}

/* Clear floats after image containers */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>


<div class="row">
  <div class="column" style="float: left; width: 95.0%; padding: 5px">
    <img src="/assets/nodesig/random_walks.png">
  </div>
  <div style="text-align:center; font-weight: bold;"><h5>Schematic representation of the NodeSig model.</h5></div>
 </div>


### Code
##### An implementation of the project in C++ can be reached at the [Github](https://github.com/abdcelikkanat/nodesig) repository.

### Contributors
##### [Abdulkadir Çelikkanat](http://abdcelikkanat.github.io/), [Apostolos N. Papadopoulos](http://delab.csd.auth.gr/~apostol/) and [Fragkiskos D. Malliaros](http://fragkiskos.me)

### References
##### A. Celikkanat, A. N. Papadopoulos and F. D. Malliaros, [NodeSig: Binary Node Embeddings via Random Walk Diffusion](.), The 2022 IEEE/ACM International Conference on Advances in Social Network Analysis and Mining (ASONAM-22), Istanbul, Turkey, 2022.
