# Column-based Precipitation Classification Algorithm

This repository features a novel column-based convection/stratiform classification algorithm based on hydrometeor information designed for applications to numerical model output and model runtime. It uses column-integrated hydrometeor information to separate convection and stratiform columns (plus additional sub-classes) based on the ratio of column-integrated ice to liquid, inspired by Sui et al. (2007, JGR). Additional criteria imposed on specific hydrometeor species are used to further separate convective and stratiform into a total of 5 categories: shallow, congestus, and deep convection; and stratiform and anvil.

The repository contains:

1) *module_ra_rrtmg_lw:* a modified version of WRF's RRTMG-LW scheme "module_ra_rrtmg_lw.F" to include the classification scheme as a switch for ICLOUD (to remove cloud interaction). That script is modified from WRFv4.3.1.
2) *cloud_ratio_class.ipynb:* a Jupyter notebook that applies and demos this new algorithm using a single time step of WRF model output.
3) *precip_class.py:* python function of the algorithm.

Coded by James Ruppert and Emily Luschen, University of Oklahoma.

**This algorithm has not yet been assessed via peer review, so caution is suggested in its use. A manuscript is now under review.**

5/18/23
