# MRS processing Scripts

Basic command-line scripts for Magnetic Resonance Spectroscopy (MRS) data preprocessing using spec2nii and FSL-MRS.

## Overview
This repository contains simple bash scripts for:
- Converting vendor-specific MRS formats → NIfTI-MRS
- Splitting dynamic MRS data along the time dimension

## Requirements
- Python (≥3.8)
- spec2nii
- FSL-MRS (full installation)

## Installation
Install spec2nii:
pip install spec2nii

Install FSL-MRS (see official documentation):
https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FSL-MRS

## Scripts

### 1. Conversion (MRS_to_NII)
Converts vendor formats (Philips, Siemens, DICOM, TWIX) to NIfTI-MRS.

### 2. Dynamic Splitting (MRS_Data_Splitting)
Splits 4D/5D NIfTI-MRS data into individual dynamics using:
mrs_tools split

## Usage
Edit input/output paths inside each script and run:
bash script_name.sh

## Notes
- Scripts are intentionally minimal and require manual parameter editing
- Designed for research workflows, not production pipelines

## Author
Arijit Bhattacharya  
Ph.D. Scholar, Ashoka University
OxCIN Global Scholar 2025-2026, The University of Oxford
