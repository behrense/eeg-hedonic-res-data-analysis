# eeg-hedonic-res-data-analysis

## Overview
This project includes EEG signal-processing techniques and basic neural data analysis workflows, such as preprocessing, filtering, and visualization.

## Features
- EEG data preprocessing
- Signal filtering
- Frequency band analysis
- Data visualization

## Tech Stack
- MATLAB
- EEGLAB
- MNE-Python
- NumPy
- Matplotlib

## Repository Structure
stage1prep/       Import, re-reference, filter, epoch, baseline, trial rejection, interpolation
stage2prep/       Removal of bad ICs, condition-specific epochs, and laplacian
stage3ssa/        Time-frequency, connectivity, ERPs, and FFTs
stage4gla/        Plotting, stats, extracting

## Dataset Source
Pohlmann, A., Reinoso-Carvalho, F., & Rodríguez, B. (2026). EEG and hedonic responses to sonic-seasoning soundscapes (Version v1.0.0) [Data set]. NEMAR. https://doi.org/10.82901/nemar.on008062
