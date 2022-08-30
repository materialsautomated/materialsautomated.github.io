# Extracting Band Gap from Hyperspectral Data
This code takes hyperspectral camera data (reflectance as a function of wavelength) and converts the data using a Kulbelka Munk transformation. 
After transforming the data, the Tauc method can be used to extract either the indirect or direct band gap (the codes does both and leaves it up to the user to decide which is appropriate).
Further, if multiple sets of data are similar in linear region, automated analysis can be performed to extract the band gap, as has been done here for Bi2WO6.
A correction function is included if needed to find the true band gap due to extra absorption peaks (see https://doi.org/10.1021/acs.jpclett.8b02892 for more detail)
If used please cite the data doi for this code and xxxx, as this paper was the inspiration to develop this code.
