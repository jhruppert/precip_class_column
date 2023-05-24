# precip_class
This repository contains:

1) *module_ra_rrtmg_lw:* a modified version of WRF's RRTMG-LW scheme "module_ra_rrtmg_lw.F" to include a column-based precipitation classification algorithm as a switch for ICLOUD (to remove cloud interaction). That script is modified from WRFv4.3.1.
2) *cloud_ratio_class.ipynb:* a Jupyter notebook that applies and demos this new algorithm using a single time step of WRF model output.
3) *precip_class.py:* python function of the algorithm.
4) *pclass_traditional.nc:* single time step output of traditional classification approach applied to WRF output (see Jupyter notebook for more info).
5) *bashrc_wrf:* a file used to set up the environment for WRF on OU's OSCER supercomputer.

Coded by James Ruppert and Emily Luschen, University of Oklahoma.

**This algorithm has not yet been assessed via peer review, so caution is suggested in its use. A manuscript is now in preparation by the authors to be submitted for peer review.**

5/18/23
