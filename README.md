# Gen_PSFMASK_ref_files
 
 The gen_psf_mask_ref_files.nb Mathematica notebook is used to create the PSF_MASK reference files using flat files for each of the coronangraphic subarrays. Each section titles with the name of a copronagraphic subarray contains a block of code using Mathematica's "Manipulate" function, which I use to overlay and align the PSF mask with the flat file (which clearly shows the correct position and outline of the coronagraphic subarray).
 
 The FITS products output by the gen_psf_mask_ref_files.nb Mathematica notebook are not yet properly formatted (Mathematica cannot properly export FITS files) - they are exported as *_npre.fits. An additional jupyter notebook is needed to properly export the FITS files with correct headers and extensions, using the *_npre.fits files as input.
