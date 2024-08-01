# Flywheel gear that implements FSL's FAST command

This gear implements a basic usage of [FSL FAST](https://fsl.fmrib.ox.ac.uk/fsl/docs/#/structural/fast). Outputs 3 mask files: CSF (csf_mask.nii.gz), white matter (wm_mask.nii.gz), grey matter (gm_mask.nii.gz).

### Inputs

* input_image: nifti file

### Configuration

* type of image 1=T1, 2=T2, 3=PD; default=T1
