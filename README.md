# FCC B2KstTauTau selection, IDEA resolutions and results

## Files description

IDEA_vertexing_study/vertex_resolution_last.ipynb : notebook use to determine IDEA (baseline and various versions) vertexing resolution  
  
Signal_vs_bkgs_selection_variables.ipynb : notebook that display the selection variables and study the preselection  
  
Signal_vs_bkgs_XGBoost.ipynb : notebook where the MVA selection is defined (train, test)  
  
sig-bkg_BF_and_DP_PS_plotter.ipynb : notebook used for the backgrounds BF guesstimates and to choose the backgrounds to consider  
  
Precision_Signal_vs_bkgs_XGBoost.ipynb : notebook used to extract the precision on the BF(B2KstTauTau) measurement as function of the vertexing resolution
  
## Python environments

Conda environment is used in order to run these notebooks:
- normally using env corresponding to environmentZFIT.yml must be ok,
- in case of troubleshooting between zfit and ROOT -> use a specific env without ZFIT when not needed (like environment.yml)

## General comments

Only the notebooks are stored in this repository, you have to use the output done from the FCC_Bd2KstTauTau_LPC gitlab repository.  
  
You have to create folders for the outputs of the notebooks.