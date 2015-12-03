# MUVR
Multivariate methods with Unbiased Variable selection in R

## General description
This is a package dedicated to predictive multivariate modelling for metabolomics.
- Model cores: PLS and Random Forest
- Data structures: Paired and unpaired
- Validation: rdCV (Westerhuis et al 2008, Filzmoser et al 2009)
- Variable selection: Performed internally.  
  The unbiased VS stems from being tuned in the inner CV loop.  

algorithm | MV-core | response | data structure | comment
:-------- | :------- | :------------- | :------ | :------
PLS-VS | PLS | class/reg | unpaired | Parallellised. Used in Hanhineva et al 2015.
ML-PLS-VS | PLS | class/reg | paired (multilevel) | Parallellised. Used in 'BioDiVa' and 'Satiety' projects.
RF-VS | Random Forest | classification | unpaired | Parallellised. Used in Buck et al 2016.
ML-RF-VS | Random Forest | classification | paired (multilevel) | Parallellised. Used in 'BioDiVa' project.

## References

Buck et al 2016

Hanhineva et al 2015

## Version history
version | date | comment
:------ | :--- | :------
0.0.900 | | Still on local git
