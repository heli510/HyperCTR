# HyperCTR

A implementation of paper “Click-Through Rate Prediction with Multi-Modal Hypergraphs”
Our code is about to be presented, Stay tuned :)

## Abstract
Advertising is critical to many online e-commerce platforms such as e-Bay and Amazon. One of the important signals that these platforms rely upon is the click-through rate (CTR) prediction. The recent popularity of multi-modal sharing platforms such as TikTok has led to an increased interest in online micro-videos. It is, therefore, useful to consider micro-videos to help a merchant target micro-video advertising better and find users' favourites to enhance user experience. Existing works on CTR prediction largely exploit unimodal content to learn item representations. A relatively minimal effort has been made to leverage multi-modal information exchange among users and items. We propose a model to exploit the temporal user-item interactions to guide the representation learning with multi-modal features, and further predict the user click rate of the micro-video item. We design a Hypergraph Click-Through Rate prediction framework (HyperCTR) built upon the hyperedge notion of hypergraph neural networks, which can yield modal-specific representations of users and micro-videos to better capture user preferences. We construct a time-aware user-item bipartite network with multi-modal information and enrich the representation of each user and item with the generated interests-based user hypergraph and item hypergraph. Through extensive experiments on three public datasets, we demonstrate that our proposed model significantly outperforms various state-of-the-art methods.

## Cite
For more information, you can take a look at the [paper](https://dl.acm.org/doi/abs/10.1145/3459637.3482327)

If you find this repo to be useful, please cite our paper. Thank you.

```
@inbook{10.1145/3459637.3482327,
author = {He, Li and Chen, Hongxu and Wang, Dingxian and Jameel, Shoaib and Yu, Philip and Xu, Guandong},
title = {Click-Through Rate Prediction with Multi-Modal Hypergraphs},
year = {2021},
isbn = {9781450384469},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3459637.3482327},
abstract = {Advertising is critical to many online e-commerce platforms such as e-Bay and Amazon. One of the important signals that these platforms rely upon is the click-through rate (CTR) prediction. The recent popularity of multi-modal sharing platforms such as TikTok has led to an increased interest in online micro-videos. It is, therefore, useful to consider micro-videos to help a merchant target micro-video advertising better and find users' favourites to enhance user experience. Existing works on CTR prediction largely exploit unimodal content to learn item representations. A relatively minimal effort has been made to leverage multi-modal information exchange among users and items. We propose a model to exploit the temporal user-item interactions to guide the representation learning with multi-modal features, and further predict the user click rate of the micro-video item. We design a Hypergraph Click-Through Rate prediction framework (HyperCTR) built upon the hyperedge notion of hypergraph neural networks, which can yield modal-specific representations of users and micro-videos to better capture user preferences. We construct a time-aware user-item bipartite network with multi-modal information and enrich the representation of each user and item with the generated interests-based user hypergraph and item hypergraph. Through extensive experiments on three public datasets, we demonstrate that our proposed model significantly outperforms various state-of-the-art methods.},
booktitle = {Proceedings of the 30th ACM International Conference on Information &amp; Knowledge Management},
pages = {690–699},
numpages = {10}
}
```


