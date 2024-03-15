# Analysis Notebooks for Reducing Variant Classification Inequalities

This repository contains the [Jupyter notebook](https://jupyter.org/) used to generate figures and key results for
"Defining and Reducing Variant Classification Inequities in Genomic Medicine" by Dawood ... Gallego Romero 
(final citation TBA).

## How to use this notebook

### Getting set up

To begin, 
[clone the repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)
so that you have a local copy of the notebook and the required directory structure.

Create a [new virtual Python environment](https://docs.python.org/3/library/venv.html) for running the notebooks.
The notebooks have been tested using Python 3.7 and Python 3.10, but other versions are likely to work as well.
Activate the environment and install the required packages defined in `requirements.txt`.

The following commands will set up and launch the notebook on a Unix-like system:

```
git clone git@github.com:MoezDawood/ReducingVariantClassificationInequities.git
cd ReducingVariantClassificationInequities
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
jupyter notebook ReducingVariantClassificationInequitiesCode_20240311.ipynb
```

### Downloading required data files

Running the notebook requires several large collections of variants from [gnomAD](https://gnomad.broadinstitute.org/)
and other sources.
Pre-formatted files can be downloaded from 
[this link](https://drive.google.com/drive/folders/1cdXoB0AMPCO0dWH_6Eff1smtCd5i5YPB?usp=drive_link)
and extracted into the `inputs/` folder in the same directory as the notebook file.

### Reproducing the results

It will take around 5-6 hours to produce all figures and tables found in the paper
(including main text figures and supplement and a few additional figures) for gnomAD v2.1.1 and gnomAD v3.1.2 (non v2).
The figures and tables will be found in the output folder.

The notebook is designed to be run from start to finish, 
but there is a table of contents and users should be able to reproduce individual figures once the setup is completed.

Note that due to the large size of the data frames containing all the required variant information,
running this notebook requires a computer with a large amount of memory and we recommend using a shared server or cluster node for this purpose.

### Data and code availability for All of Us

Per the policy of the All of Us program, the code, inputs, and outputs for the All of Us analyses is in a declared workspace in the All of Us workbench.
The code in the All of Us workspace is the same as below with modifications made for the specific data requirements of the All of Us platform.
The workspace will be gladly and immediately shared with approved users upon request.
