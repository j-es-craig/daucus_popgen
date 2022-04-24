# daucus_popgen
## Testing QPC (Josephs et al 2019) on _Daucus carota_

QPC is a new method for detecting signals of natural selecction from genomic and phenotype data. 
By extracting the principal components from a SNP matrix, we can project trait vectors over the SNP eigenvectors, and
via an F-test, test for variation exceeding neutral expectations, i.e. natural selection.

Within are scripts for applying the method to a dataset of _Daucus carota_, as well as scripts for visualizing the results
using base R and ggplot2. 
