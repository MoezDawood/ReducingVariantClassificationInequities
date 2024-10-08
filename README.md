# Analysis Code for 'Using Multiplexed Functional Data to Reduce Variant Classification Inequities in Underrepresented Populations'

## Citation
Preprint: Dawood, M., et al. "Defining and Reducing Variant Classification Disparities." medRxiv (2024): 2024-04.
DOI: https://doi.org/10.1101/2024.04.11.24305690

Code Repository: [![DOI](https://zenodo.org/badge/770433357.svg)](https://zenodo.org/doi/10.5281/zenodo.13883266)

## Jupyter 

Before beginning, you will need Jupyter (https://jupyter.org/install) to view and interact with the Jupyter notebook.


## Notebook Instructions

1. First clone and download the github repository. Then download the input data from zenodo at [![DOI](https://zenodo.org/badge/770433357.svg)](https://zenodo.org/doi/10.5281/zenodo.13883266)


    In the Archive.zip (~2.2 GB) there will be two folders: requiredinputs and exampleoutput. Put all the files without changing their names from the requiredinputs folder into the `inputs/` folder (from the cloned and downloaded github repo). The exampleoutput folder is for comparison. After unzipping the total size for all the files is about ~12.5 GB.

    
    

2. Run notebook from top to bottom in order. If the entire github repository is downloaded and the contents are kept in the same order then you can click the 'Run all below' button.


3. Python version 3.7.7 was used to run this notebook.


4. The R version is R version 4.2.2 (2022-10-31). This is very pertinent for the rpy2 installation. If possible install rpy2 v3.5.7 and ggstatsplots v0.12.1


5. Please make sure to use a similar and compatible version of python otherwise some packages may be outdated or function differently.


6. Will take around 8-9 hours to produce all figures and tables found in the paper (including main text figures and supplement and a few additional figures) for gnomAD v2.1.1 and gnomAD v3.1.2 (non v2). The figures and tables used in the paper can be found in-line as outputs of this jupyter notebook as well as in the output folder. Complete rankings across all three databases of all clinically curated genes by VUS/PorLP/BorLB/CI/ND allele prevalence difference can be found in the exampleoutput folder.


7. Per the policy of the All of Us program, the code, inputs, and outputs for the All of Us analyses are in a declared workspace in the All of Us workbench. The code in the All of Us workspace is the same as below with modifications made for the specific data requirements of the All of Us platform. After publication, the workspace will be gladly and immediately shared with approved users upon request.



