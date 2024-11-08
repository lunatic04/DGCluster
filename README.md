# DGCLUSTER: A Neural Framework for Attributed Graph Clustering via Modularity Maximization

This repository is a reference implementation of DGCluster as described in the paper:
<br/>
> DGCLUSTER: A Neural Framework for Attributed Graph Clustering via Modularity Maximization.<br>
> Aritra Bhowmick, Mert Kosan, Zexi Huang, Ambuj Singh, Sourav Medya<br>
> Association for the Advancement of Artificial Intelligence (AAAI), 2024.<br>
> [https://ojs.aaai.org/index.php/AAAI/article/view/28983](https://ojs.aaai.org/index.php/AAAI/article/view/28983)






## Reproducing Results

To generate the result for a specific dataset (e.g., cora) and lambda parameter (e.g., 0.2), run the following:

```train
python main.py --dataset cora --lam 0.2
```


Additionally, `plots.py` and `plots_num_clusters.py` can be used to generate Figure 1 and Figure 2.
