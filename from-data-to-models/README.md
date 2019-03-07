# From Data To Models To Analytics

This project is a collaboration between Kitware and Lawrence Berkeley
National Laboratory (LBNL) beginning in 2018. The main goal is to
develop an open-source, integrated computing and analytics platform
in the Environmental Systems Science (ESS) space that combines the
power of high performance computing with interactive analytics for
exploratory analyis while providing an intuitive and familiar user
experience to researchers. Specific objectives include developing a
web-based interface for reproducible workflows, provide a unified
interface to external data and metadata, develop high-performance
visualization of environmental data, simplify the submission and
management of remote computing on HPC or cloud-based systems, and
ensure easy deployment and installation.

This folder contains the docker files and other scripts used to build
and deploy the Girder-based server for this project. Key girder plugins
include:

* Girder Worker for running background tasks
* geometa for capturing meta data from environmental files and datasets
* girder-ess-dive to interface with the DOE ESS-DIVE archive as a
  Girder assetstore
* large_image for efficient display of raster datasets
* resonantgeodata for preprocessing operations such as reprojection and
  cropping
