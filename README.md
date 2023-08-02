# MIRI_MRS
**JWST MIRI/MRS reduction pipeline for point sources**

**Objective:**

Some MIRI/MRS targets are either located in regions with high/complicated backgrounds, are too faint, or both. This is an attempt to find a better way than what the current pipeline offers to subtract/mitigate the effect of these high background regions. The official pipeline uses an annulus around the target to subtract the background, which is not ideal in cases with highly varying backgrounds. 

**This notebook shows:**

1) How to construct a background that is more representative of the background variation
2) How to subtract the background and extract the final spectrum


If you use this notebook, please consider citing the GitHub link (https://github.com/shahbandeh/MIRI_MRS) and Shahbandeh et al. 2023b (in prep)
