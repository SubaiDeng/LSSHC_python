# LSSHC_python
This repository is python code of the paper " [GraphLSHC: Towards Large Scale Spectral Hypergraph Clustering](https://www.sciencedirect.com/science/article/pii/S0020025520306824)".

If you want to use the code, please cite 

**BibTex**

```
@article{YANG2021117,
title = "GraphLSHC: Towards large scale spectral hypergraph clustering",
journal = "Information Sciences",
volume = "544",
pages = "117 - 134",
year = "2021",
issn = "0020-0255",
doi = "https://doi.org/10.1016/j.ins.2020.07.018",
url = "http://www.sciencedirect.com/science/article/pii/S0020025520306824",
author = "Yiyang Yang and Sucheng Deng and Juan Lu and Yuhong Li and Zhiguo Gong and Leong Hou U and Zhifeng Hao",
keywords = "Machine Learning, Unsupervised Learning, Clustering, Hypergraph",
abstract = "Hypergraph is popularly used for describing multi-relationships among objects in a unified manner, and spectral clustering is regarded as one of the most effective algorithms for partitioning those objects (vertices) into different communities. However, the traditional spectral clustering for hypergraph (HC) incurs expensive costs in terms of both time and space. In this paper, we propose a framework called GraphLSHC to tackle the scalability problem faced by the large scale hypergraph spectral clustering. In our solution, the hypergraph used in GraphLSHC is expanded into a general format to capture complicated higher-order relationships. Moreover, GraphLSHC is capable to simultaneously partition both vertices and hyperedges according to the “eigen-trick”, which provides an approach for reducing the computational complexity of the clustering. To improve the performance further, several hyperedge-based sampling techniques are proposed, which can supplement the sampled matrix with the whole graph information. We also give a theoretical guarantee for the error boundary of the supplement. Several experiments show the superiority of the proposed framework over the state-of-the-art algorithms."}
```


# Environment
python 3.7, sklearn 0.23.0, scipy 1.5.2, numpy 1.19.0

# Run
`python lsshc.py`

# Remark
The matlab version is available at

https://github.com/SubaiDeng/LSSHC_matlab
