# Visualization of data in a THREDDS server

Thematic Real-time Environmental Distributed Data Services (THREDDS) is a service developed by Unidata to simplify the cataloging and access of large environmental datasets. The open-source THREDDS data server can be deployed to manage a large collection of spatio-temporal datasets typically in the NetCDF format. The associated data catalog manages the metadata about the dataset which can be used to identify the spatio-temporal extents and the data variables contained in the datasets. 

Various data access protocols can be used to access data managed by a THREDDS server. In particular, the OpeNDAP protocal can be used to access subsets of the dataset across the spatial and temporal domains, as well as specific data variables. The notebook in this repository demonstrates how to how to access, subset, and visualize Analysis of Record for Calibration (AORC) forcing micrometeorological data that is stored in the Thredds catalog hosted by the Hydroshare gateway.

[Open in I-GUIDE Platform](https://jupyter.iguide.illinois.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FI-GUIDE%2Fthredds_data_visualization&urlpath=lab%2Ftree%2Fthredds_data_visualization%2Faorc-hs-thredds.ipynb+&branch=main)
