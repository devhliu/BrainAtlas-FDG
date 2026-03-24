# Brain Atlas - FDG

## Overview

This repository contains age-dependent and 3D Hoffman phantom harmonized 18F-FDG brain PET atlases generated using a high-sensitivity short-axial FOV PET/CT system. The atlases are provided in MNI space with different smoothing kernels for various neuroimaging applications.

## Atlas Structure

The repository contains two main atlas directories with different Gaussian smoothing kernels:

### FDG_MNISpace_EIR_5-6mm
Atlases smoothed with 5-6mm Gaussian kernel, suitable for high-resolution analysis:
- `Y20-30_SUVr_mni_atlas.nii.gz` - Atlas for age group 20-30 years
- `Y30-40_SUVr_mni_atlas.nii.gz` - Atlas for age group 30-40 years
- `Y40-50_SUVr_mni_atlas.nii.gz` - Atlas for age group 40-50 years
- `Y50-60_SUVr_mni_atlas.nii.gz` - Atlas for age group 50-60 years
- `Y60-70_SUVr_mni_atlas.nii.gz` - Atlas for age group 60-70 years
- `Y70-80_SUVr_mni_atlas.nii.gz` - Atlas for age group 70-80 years
- `Y80-90_SUVr_mni_atlas.nii.gz` - Atlas for age group 80-90 years

### FDG_MNISpace_EIR_8-10mm
Atlases smoothed with 8-10mm Gaussian kernel, suitable for standard clinical applications:
- `Y20-30_SUVr_mni_atlas.nii.gz` - Atlas for age group 20-30 years
- `Y30-40_SUVr_mni_atlas.nii.gz` - Atlas for age group 30-40 years
- `Y40-50_SUVr_mni_atlas.nii.gz` - Atlas for age group 40-50 years
- `Y50-60_SUVr_mni_atlas.nii.gz` - Atlas for age group 50-60 years
- `Y60-70_SUVr_mni_atlas.nii.gz` - Atlas for age group 60-70 years
- `Y70-80_SUVr_mni_atlas.nii.gz` - Atlas for age group 70-80 years
- `Y80-90_SUVr_mni_atlas.nii.gz` - Atlas for age group 80-90 years

## Features

- **Age-Dependent**: Separate atlases for different age decades (20-90 years)
- **Harmonized**: Atlases harmonized using 3D Hoffman phantom
- **MNI Space**: All atlases are in standard MNI space for easy integration
- **Multiple Smoothing Kernels**: Two smoothing options for different application needs
- **SUVr Normalized**: Standardized Uptake Value ratio normalized for quantitative analysis

## Usage

These atlases can be used for:
- Normal database comparison in clinical FDG-PET studies
- Age-specific reference for detecting hypometabolism
- Voxel-based analysis in neurodegenerative disease research
- Harmonization of multi-center FDG-PET studies

## Data Format

- All atlas files are in NIfTI format (.nii.gz)
- Spatial resolution: MNI standard space
- Intensity: SUVr (Standardized Uptake Value ratio)

## License

This project is licensed under the MIT License - see the [License](License) file for details.

## Citation

If you use these atlases in your research, please cite:

1. Wei YD, Zhang SX, Wen QX, Yin LJ, Yang S, Liu P, Zhou Z, Fu LP. Generation of an Age-Dependent and Harmonized 18F-FDG Brain PET Atlas Using a High-Sensitivity Short-Axial FOV PET/CT System. Hum Brain Mapp. 2026 Mar;47(4):e70502. doi: 10.1002/hbm.70502.

## Contact

For questions or issues, please contact the corresponding author Liping Fu.
