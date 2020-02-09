---
layout: EFGE
---
## <center>Exponential Family Graph Embeddings</center>
### Description
<h5 align="justify">
We emphasize on exponential family distributions to capture rich interaction patterns between nodes in random walk sequences. We introduce the generic <i>exponential family graph embedding</i> model, that generalizes random walk-based network representation learning techniques to exponential family conditional distributions. We study three particular instances of this model, analyzing their properties and showing their relationship to existing unsupervised learning models. Our experimental evaluation on real-world datasets demonstrates that the proposed techniques outperform well-known baseline methods in two downstream machine learning tasks.
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
  <div class="column" style="float: left; width: 18.6%; padding: 5px">
    <img src="/assets/efge/dolphins_2comm_eigen-1.jpg">
    <div style="text-align:center; font-weight: bold;"><h6>Dolphins Network</h6></div>
  </div>
  <div class="column" style="float: left; width: 18.6%; padding: 5px">
    <img src="/assets/efge/dolphins_deepwalk_dim=2_eigen-1.jpg">
    <div style="text-align:center; font-weight: bold;"><h6>DeepWalk</h6></div>
  </div>
  <div class="column" style="float: left; width: 18.6%; padding: 5px">
    <img src="/assets/efge/dolphins_method1_dim=2_eigen-1.jpg">
    <div style="text-align:center; font-weight: bold;"><h6>EFGE-Bern</h6></div>
  </div>
  <div class="column" style="float: left; width: 18.6%; padding: 5px">
    <img src="/assets/efge/dolphins_method2_dim=2_eigen-1.jpg">
    <div style="text-align:center; font-weight: bold;"><h6>EFGE-Pois</h6></div>
  </div>
   <div class="column" style="float: left; width: 18.6%; padding: 5px">
    <img src="/assets/efge/dolphins_method4_exp_dim=2_eigen-1.jpg">
    <div style="text-align:center; font-weight: bold;"><h6>EFGE-Norm</h6></div>
  </div>
  <div style="text-align:center; font-weight: bold;"><h6>The <i>Dolphins</i> network composed by 2 communities and the corresponding embeddings for <i>d=2</i></h6></div>
 </div>


### Code
##### An implementation of the project in C++ can be reached at the [Github](https://github.com/abdcelikkanat/EFGE) repository.

### Contributors
##### [Abdulkadir Çelikkanat](http://abdcelikkanat.github.io/) and [Fragkiskos D. Malliaros](http://fragkiskos.me)

### References
##### A. Celikkanat and F. D. Malliaros, [Exponential Family Graph Embeddings](https://arxiv.org/pdf/1911.09007.pdf), The Thirty-Fourth AAAI Conference on Artificial Intelligence (AAAI-20), New York City, New York, 2020.
