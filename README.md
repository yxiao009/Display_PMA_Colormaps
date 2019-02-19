# Display_PMA_Colormaps

Assume we already calculated the perfusion maps through some methods. Let’s call the generated perfusion maps as CBF and CBV (2D matrix).

Requirements: (everything is in the folder /Display_PMA_Colormaps_Yao) 
- Full PMA Color Lookup Table (CLT) from PMA software, PMA_lut.csv
- Function select_colormap.m  % select the PMA colormap that you want to display 
- Function ctshow_pma.m       % display images with defined colormap
- CBF.mat, CBV.mat, mask.mat  % required data for displaying (pre-calculated)

Example:
Run example_ctshow_pma_colormap_full.m

Resulted image:
