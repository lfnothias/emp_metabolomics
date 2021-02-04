# EMP metabolomics

The latest metabolomics jobs and methods are available on that repository [https://github.com/lfnothias/emp/blob/release_2.1/methods/methods_release2.md](https://github.com/lfnothias/emp/blob/release_2.1/methods/methods_release2.md).

The notebooks below were used to preanalysis and prepare the metabolomics results.


## emp_metabolomics_concatenate_annotations
'EMP_Metabo_FBMN_CMN_Concat_Annotations.ipynb'

This notebooks takes all the annotations available and concatenate them into a master feature metadata table.

Interative notebook here -> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lfnothias/emp_metabolomics_quickvisualization/HEAD?filepath=EMP_Metabo_FBMN_CMN_Concat_Annotations.ipynb)


## emp_metabo_FBMN_visualize
'EMP_Metabo_FBMN_visualize-distrib_v4.ipynb'

This notebook visualized the intensity distribution in the metabolomics feature intensity table. That informations helps to define an intensity threshold for noise and for abscence/presence of a compound.
Two feature tables are used (before/after gap filling) and for simplicity, we use a subset of samples.

Interative notebook here -> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lfnothias/emp_metabolomics_quickvisualization/HEAD?filepath=EMP_Metabo_FBMN_visualize-distrib_v4.ipynb)

Interative notebook to compare before/after gap filling here -> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lfnothias/emp_metabolomics_quickvisualization/HEAD?filepath=EMP_Metabo_FBMN_visualize-distrib_v3_compare_before_after_gapfilling.ipynb)


## emp_metabolomics_feature_table_to_biom
'EMP_metabo_MZmine_to_BIOM.ipynb'

This notebooks takes a MZmine feature table and convert it into the BIOM format.

Interative notebook here -> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lfnothias/emp_metabolomics_quickvisualization/HEAD?filepath=EMP_metabo_MZmine_to_BIOM.ipynb)