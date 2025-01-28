# Disease-subtype-discovery-using-multi-omics-data-integration
The project regards the discovery of disease subtypes using a multi-omics dataset coming from TGCA.
The dataset is the Prostate adenocarcinoma dataset (disease code "PRAD"). 

In this study, we leverage two approaches for multi-omics data integration: 
- a graph-based algorithm called Similarity Network Fusion (SNF)
- a simple averaging of similarity matrices

For clustering, we utilize:
- Partitioning Around Medoids (PAM)
- Spectral Clustering

Our goal is to evaluate whether the clusters derived from these multi-omics integration and clustering methods 
correspond to the molecular subtypes identified by the iCluster integrative model used by The Cancer Genome Atlas Research Network.
