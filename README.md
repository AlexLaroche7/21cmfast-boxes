# 21cmfast-boxes
Boxes for 21CMFAST Simulations with X-ray Heating Included

'E0_1500_filter_boxes' contains inside-out and outside in simulations for NU_X_THRESH = 1500 eV. This outside in model is composed of flipped spin temperature
and original density and ionized fraction. The simulation specs are given in the title of each figure. 'single' folders contain individual box plots,
whereas 'combo' folders contain paired box plots. All figures include the full field, and 3 k-filtered fields: k=[0.05,0.15], k=[0.45,0.55] and k=[0.8,0.9].
Redshifts z = 8.0 to z = 18.0 were sampled at dz = 0.5.

'E0_500_filter_boxes' is the same as the above, except NU_X_THRESH = 500 eV. This is the default 21CMFAST value.

'power_spectra.png' contains the resulting power spectra from the 'E0_1500_filter_boxes' and 'E0_500_filter_boxes' simulations. Power spectra are at fixed k
and varying z. All power spectra curve labels correspond to the labels given in the box folders.

These plots were produced by Alex Laroche and Joey Banghal using 21CMFAST (https://github.com/21cmfast).
