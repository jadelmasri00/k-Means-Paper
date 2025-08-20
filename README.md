Pack and Select: An Effective K-Selection Method for K-Means Clustering

This repository contains my research paper, “Pack and Select: An Effective K-Selection Method for K-Means Clustering.”
The PDF is included as Pack_and_Select.pdf.

What this work is about

Choosing the right number of clusters K is a persistent challenge in K-means. Common heuristics (e.g., elbow or index-based rules) can be sensitive to dataset shape, density, and overlap.

Pack and Select reframes K-selection with a simple graph-based idea:

Build a distance view of the data and set an adaptive distance threshold d from the data itself.

Find a minimal d-packing—a set of points that are all at least d apart.

Use the size of that packing as a strong estimate for K.

Intuitively, the packing picks well-separated “representatives.” Their count provides a stable, data-aware estimate of how many clusters are present. The procedure is lightweight and fits naturally alongside K-means initialization or model selection workflows.

Code availability

The implementation and experiment scripts are private while the paper is under review for publication. 

