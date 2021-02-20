# EMP metabolomics

The latest *metabolomics data/jobs/results* and methods are available from that repository [https://github.com/lfnothias/emp/blob/release_2.1/methods/methods_release2.md](https://github.com/lfnothias/emp/blob/release_2.1/methods/methods_release2.md).

The notebooks below were used to preanalysis and prepare the metabolomics results, including the feature metadata master tables.

The latest *feature metadata* master tables for Feature-Based Molecular Networking (*FBMN*) and Classical Molecular Networking (*CMN*) are in [metabo_feature_metadata](./metabo_feature_metadata).


## Prepare feature metadata
[`EMP_Metabo_FBMN_CMN_Concat_Annotations.ipynb`](https://nbviewer.jupyter.org/github/lfnothias/emp_metabolomics/blob/main/notebooks/EMP_Metabo_FBMN_CMN_Concat_Annotations.ipynb)

This notebooks takes all the annotations available and concatenate them into a master feature metadata table.

Interative notebook here -> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lfnothias/qiime2/master?urlpath=lab/tree/notebooks/EMP_Metabo_FBMN_CMN_Concat_Annotations.ipynb)


## Visualize intensity distribution in FBMN
[`EMP_Metabo_FBMN_visualize-distrib_v4.ipynb`](https://nbviewer.jupyter.org/github/lfnothias/emp_metabolomics/blob/main/notebooks/EMP_Metabo_FBMN_visualize-distrib_v4.ipynb)

This notebook visualized the intensity distribution in the metabolomics feature intensity table. That informations helps to define an intensity threshold for noise and for abscence/presence of a compound.
Two feature tables are used (before/after gap filling) and for simplicity, we use a subset of samples.

Interative notebook here -> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lfnothias/qiime2/master?urlpath=lab/tree/notebooks/EMP_Metabo_FBMN_visualize-distrib_v4.ipynb)

Interative notebook to compare before/after gap filling here -> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lfnothias/qiime2/master?urlpath=lab/tree/notebooks/EMP_Metabo_FBMN_visualize-distrib_v3_compare_before_after_gapfilling.ipynb)


## Convert MZmine table to BIOM
[`EMP_metabo_MZmine_to_BIOM.ipynb`](https://nbviewer.jupyter.org/github/lfnothias/emp_metabolomics/blob/main/notebooks/EMP_metabo_MZmine_to_BIOM.ipynb)

This notebooks takes a MZmine feature table and convert it into the BIOM format.

Interative notebook here -> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lfnothias/qiime2/master?urlpath=lab/tree/notebooks/EMP_metabo_MZmine_to_BIOM.ipynb)


## Consolidate structures identifiers
[`EMP_Metabo_Annotations_consolidate_CMN.ipynb`](https://nbviewer.jupyter.org/github/lfnothias/emp_metabolomics/blob/main/notebooks/EMP_Metabo_Annotations_consolidate_CMN.ipynb)
[`EMP_Metabo_Annotations_consolidate_FBMN.ipynb`](https://nbviewer.jupyter.org/github/lfnothias/emp_metabolomics/blob/main/notebooks/EMP_Metabo_Annotations_consolidate_FBMN.ipynb)

This notebooks consolidate structure identifiers.

Interative notebook here -> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lfnothias/qiime2/master?urlpath=lab/tree/notebooks/EMP_Metabo_Annotations_consolidate_CMN.ipynb)

Interative notebook here -> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lfnothias/qiime2/master?urlpath=lab/tree/notebooks/EMP_Metabo_Annotations_consolidate_FBMN.ipynb)

## Establish microbial metabolites and propagate
[`EMP-metabo_CMN_microbial_metabolites.ipynb`](https://nbviewer.jupyter.org/github/lfnothias/emp_metabolomics/blob/main/notebooks/EMP-metabo_CMN_microbial_metabolites.ipynb)
[`EMP-metabo_FBMN_microbial_metabolites.ipynb`](https://nbviewer.jupyter.org/github/lfnothias/emp_metabolomics/blob/main/notebooks/EMP-metabo_FBMN_microbial_metabolites.ipynb)

This notebooks consolidate structure identifiers.

Interative notebook here -> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lfnothias/qiime2/master?urlpath=lab/tree/notebooks/EMP-metabo_CMN_microbial_metabolites.ipynb)

Interative notebook here -> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lfnothias/qiime2/master?urlpath=lab/tree/notebooks/EMP-metabo_FBMN_microbial_metabolites.ipynb)