# Interpolating Magnetization Data for Magnetocaloric Effect Calculations
This code takes magnetizaton data (magnetization as a function of temperature and applied field) and interpolates the data using scipy.interpolate. 
An application of such an interpolation is the calculation of the magnetic entropy change:
<img src="https://latex.codecogs.com/svg.image?\Delta&space;S_{M}(T,\Delta&space;H)=\int_{H_{1}}^{H_{2}}(\frac{\partial&space;M(T,H)}{\partial&space;T})dH" />\
The integration of the magnetization data requires a large amount of measurements, which can be time consuming. Thus interpolated data can help reduce the amount of measurement time needed to determine this value.
## Referencing
Please cite Materials Automated when using this code for interpolation. If the code is used for the magnetocaloric caloric calculation, cite https://doi.org/10.1103/PhysRevB.97.100404
