p# Quality_Control
It can be challenging to acquire MR images of consistent quality or to decide in the screening of large databases, which dataset is of sufficient quality for further processing. Manual screening without quantitative criteria is strictly user-dependent and not feasible for huge databases. In contrast to clinical MRI, in preclinical, animal imaging, there is no consensus on standardization of quality control measures or categorization of good vs. bad quality images.  The Atlas-based Processing Pipeline for for Quality Control of Animal MRI Data(AIDAqc) was developed for measuring ans standardizing the quality of mouse brain MRI in a dynamic and novel way. AIDAqc works with T2-weighted MRI (T2w), diffusion weighted MRI or diffusion tensor imaging (DTI) and resting-state functional MRI (fMRI).   Here, we developed a tool in Python to create a basic overview about MR image datasets including information about the SNR, temporal SNR, spatial resolution, and movement severity (Figure 1). Currently this tool covers T2w, DWI, and fMRI sequences. 

A test dataset can be downloaded here: https://gin.g-node.org/arefks/AIDAqc_test_data
