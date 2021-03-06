# Vector Correction for DWI data 
**`vector_corr`** is a handy script to undestrand the steps for correcting the diffusion vectors (bvecs) when the adquisition matrix is angled.    
This requires and updated version or **mrtrix**, the angled matrix from the adquisition of the DWI (omat), bvecs and bvals in column format, and the text file of corrected.eddy parameters obtained after topup/eddy from FSL.  
> 1. To use this script, dowload the source code of `vector_corr` and `rotateBvec.py` to a local directory.  
> 2. Make sure that both are executable (chmod +xX).  
> 3. Change line 134 of `vector_corr` to you local path.  
  
>*Further reading:* Leemans, A., & Jones, D. K. (2009). The B‐matrix must be rotated when correcting for subject motion in DTI data. Magnetic resonance in medicine, 61(6), 1336-1349.  
