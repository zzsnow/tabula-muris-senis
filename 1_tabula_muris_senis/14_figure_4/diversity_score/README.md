## Diversity score analysis for **Tabula Muris Senis**
- `cluster_mouse_tissue.ipynb` clusters cells from all method-mouse-tissue combinations using six clusetering configurations ('louvain', 'leiden') $\times$ resolution parametesr (0.3, 0.5, 0.7). 
- `cluster_mouse_tissue_downstream.ipynb` contains all the downstream analysis.
- `helper.py` contains some helper functions. 

## Toy example
For readers who wish to perform similar analyses, we provided a self-contained example in `demo.ipynb` to better explain how we performed the diversity score analysis. Here, we 

- clustered the FACS brain_myloid and marrow data, 
- computed the diversity score and p-values, 
- and visualized the results, similar to ones we did in the paper. 

The demo only relies on an external data [link](https://figshare.com/articles/Diversity_score_toy_data/11340128) (234MB). It does not depend on other customized code. So it should be more user-friendly.  
