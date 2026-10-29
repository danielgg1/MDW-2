# MDW-2
Assignment 2 for the INFOMDW course

This code file is part of the second assignment of the INFOMDW course. It demonstrates an implementation of LLE (Locally Linear Embeddings) in Python by creating a swiss roll, compressing it into two dimensions, and showing that it maintains the proximity of neighbors. Also, the performance of LLE is compared to PCA.

# Requirements

- Python 3.11+
- Installed packages: pandas 3.0.6, matplotlib 3.11.2, and sklearn 1.9.1. 

The data is generated in the code, so no external data sources are needed.

# Running the code
To run the code, the code.ipynb should be opened in a Jupyter notebook environment. 

# Used parameters
| Method   | Parameter    | Value   |
| -------- | ------------ | ------- |
| PCA      | n_components |   2     |
| LLE      | neighbors    |   25    |
| LLE      | neighbors    |   4     |
| LLE      | neighbors    |   150   |

The parameters have been evaluated using the visualisations.
