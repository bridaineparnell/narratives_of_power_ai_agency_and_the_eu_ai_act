# Narratives of Power: AI, Agency and the EU AI Act

This repository houses the code used for computational critical discourse analysis for the article Narratives of Power: AI, Agency and the EU AI Act. The dataset consists of media articles and interviews which cannot be publicly redistributed without license.

This code uses:

### BERTopic 
(Grootendorst, M. (2022) ‘BERTopic: Neural topic modeling with a class-based TF-IDF procedure’. Available at: https://arxiv.org/abs/2203.05794v1), 
### all-mpnet-base-v2 
(Reimers, N. and Gurevych, I. (2019) ‘Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks’, in K. Inui et al. (eds) Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP). EMNLP-IJCNLP 2019, Hong Kong, China: Association for Computational Linguistics, pp. 3982–3992. Available at: https://doi.org/10.18653/v1/D19-1410),
### UMAP 
(McInnes, L., Healy, J. and Melville, J. (2020) ‘UMAP: Uniform Manifold Approximation and Projection for Dimension Reduction’. arXiv. Available at: https://doi.org/10.48550/arXiv.1802.03426), and
### HDBSCAN 
(McInnes, L., Healy, J. and Astels, S. (2017) ‘hdbscan: Hierarchical density based clustering’, The Journal of Open Source Software, 2(11), p. 205. Available at: https://doi.org/10.21105/joss.00205)

It performs topic modelling, and a latent semantic analysis using keywords to create lists for seed topics to uncover subtextual narratives.

It also generates a random sample of documents given specific parameters.
