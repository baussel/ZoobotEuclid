#### Dataset_Creation.ipynb
Takes the publicly available csv files from GZH and saves for the utilized questions the number of volunteers who selected a certain answer.

#### FITS_Creation_Hubble.ipynb
Downloads the HST COSMOS FITS files and saves for every galaxy of GZH a 300x300px greyscale FITS file with 3xKron radius with the galaxy in the center.

#### FITS_Creation_Euclid.ipynb
Takes the provided emulated Euclid FITS file (generated from HST COSMOS images) and saves for every galaxy of GZH a 300x300px greyscale FITS file with 3xKron radius with the galaxy in the center.

#### HST_Creation_Hubble.ipynb and JPG_Creation_Euclid.ipynb
Imports the 300x300px FITS files, applies for every image an arcsinh intensity mapping (as described in http://ds9.si.edu/doc/ref/how.html) and saves them as 300x300px JPG files.
