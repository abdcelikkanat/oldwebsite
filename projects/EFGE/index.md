---
layout: EFGE
---
## <center>Exponential Family Graph Embeddings</center>
### Motivation
##### Representing networks in a low dimensional latent space is a crucial task with many interesting application in graph learning problems, such as link prediction and node classification. A widely applied network representation learning paradigm is based on the combination of random walks for sampling context nodes and the traditional *Skip-Gram* model to capture center-context node relationships. In this paper, we emphasize on exponential family distributions to capture rich interaction patterns between nodes in random walk sequences. We introduce the generic *exponential family graph embedding* model, that generalizes random walk-based network representation learning techniques to exponential family conditional distributions. We study three particular instances of this model, analyzing their properties and showing their relationship to existing unsupervised learning models. Our experimental evaluation on real-world datasets demonstrates that the proposed techniques outperform well-known baseline methods in two downstream machine learning tasks.


### Code
##### An implementation of the project in C++ can be reached at the [Github](https://github.com/abdcelikkanat/EFGE) repository.

### Contributors
##### [Abdulkadir Çelikkanat](http://abdcelikkanat.github.io/) and [Fragkiskos D. Malliaros](http://fragkiskos.me)

### References
##### A. Celikkanat and F. D. Malliaros, [Exponential Family Graph Embeddings](https://arxiv.org), The Thirty-Fourth AAAI Conference on Artificial Intelligence (AAAI-20), New York City, New York, 2020.
