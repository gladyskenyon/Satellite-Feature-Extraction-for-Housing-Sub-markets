# Satellite-Feature-Extraction-for-Housing-Sub-markets
The following repository includes the code and data to implement the analysis for the paper 'Extracting features from satelleite imagery to understand the size and scale of housing sub-markets in Madrid'.

1. sub_mark_final(1).ipynb 
This notebook contains the code for the majority of the analysis. It includes pulling the satelleite imagery using an API, dividing it into patches, extracting features, clustering the features and calculating internal validation scores.

3. join_housing.ipynb
This requires the outputs of sub_mark_final(1). The code introduces the housing listings data, joins the data to the cluster labels and calculates the within-cluster variation in housing attributes.

5. regression_submarkets.ipynb
This notebook takes the outputs of the first two analysis and runs various regression models using the validation metrics.

6. Paper_figrues.ipynb
This notebook produces the plots included as figures in the paper.
