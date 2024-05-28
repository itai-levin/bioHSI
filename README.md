#bioHSI
This repository contains the code for the discovery of hyperspectral reporter
molecules and the processing of collected hyperspectral images. 
The code is organized into directories that represent standalone modules for the
 different aspects of the work. Each directory contains a README file to guide users. 

 ### Directories:
 - `00_biomolecular_network`: Scripts and notebooks to process biomolecular reaction databases,
 extract metabolites, define host metabolomes, construct biochemical reaction network
 and perform shortest path search to assess ease of biosynthesis of heterolous metabolites [NOBOI]
 - `01_spectral_prediction`: Scripts to run TD-DFT spectral prediction pipeline to go 
 from metabolite structures to predicted spectra.  [BIOSPECTRAL]
 - `02_reporter_ranking`: Scripts to compute the uniqueness of molecules compared to other
 metabolites and to compute contrast to hyperspectral images. Also contains benchmarking scripts. [SPECTRANALYSIS]
 - `03_image_processing`: Scripts to classify presence of reporter in experimentally collected hyperspectral images. [HSI_DETECT/ANALYHSIS]