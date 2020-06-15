# About me

This repository contains the codes developed for setting up a PANDA motion compensation pipeline for AMS datasets. 

# Code legends

- convert-Ecat-2-Nii.ipynb: This is a jupyter notebook which is used to convert the ECAT data from AMS to NIFTI using the 'xmedcon' library, PANDA at this point needs NIFTI format as input. For this script to run, xmedcon library needs to be compiled in your workstation (https://xmedcon.sourceforge.io/Main/Download)

- auto_model_match_inference.ipynb: This jupyter notebook contains scripts for the automatic temporal-matching of the VIE models (SMS) to the AMS dynamic frames (PHLPS)and infering them on the fly. You need to install the PANDA library and its dependencies (it has a buck load of dependencies) first. This is just a script for temporally-matched smart inference.



# Note 

All the ipynb notebooks can be converted to native python scripts, but argument parsers need to be in place.
