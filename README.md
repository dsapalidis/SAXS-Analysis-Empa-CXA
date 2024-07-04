# SAXS-Analysis-Empa-CXA
Python/Jupyter tools for Small-Angle X-ray Scattering data processing

<h1 align="center">
<img src="https://github.com/dsapalidis/mypackage/blob/Sapd-Tutorial/Sapaempa.svg" width="400">
</h1><br>

   
SAXS software and tools is a Python package containing mostly jupyter notebooks that enables:
1. Reading the exported .tiff images from X-Area and load them
2. Resizing them if they don’t match in pixel dimensions
3. Subtraction of the background image using a user defined bck coefficient
4. Showing the background subtracted image directly in order to help user find the proper background coefficient
5. Detection of the beamstop automatically on the plate image
6. Calculation and storage of the radius, the 2-theta value and the intensity of each pixel of the image
7. Integration of the image employing user's defined sections
8. Fitting of the 1D data using various types of peaks
   

- **Website:** https://www.empa.ch/web/s499
- **Bugs** dsapalidis@gmail.com
