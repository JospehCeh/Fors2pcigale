# README.md

Tools to prepare io for gelato to measure emission lones


## 1) Compare spectrum in observation frame with spectrum redshifted in restframe

- **AccessFors2Spectra.ipynb** : It really convince that spectra are given in obs frame and that it i up  to us to put it in restframe

## 2) Compare the spectrum loaded with the original png image of the spectrum showing the emission lines

- **AccessFors2Spectra_comparewithimage.ipynb** : Compare the image in the png file with the spectrum loaded. It is again obvious that Fors2 spectra are given in observation frame

## 3) Compare the spectra with filters transmission
- **AccessFors2Spectra_withfilters.ipynb** : to view which photometric filters are in the range of the observed spectrum

## 4) Calibrate the spectrum flux in erg/cm2/s/AA 
- **AccessFors2Spectra_withfilters.ipynb**, - **AccessFors2Spectra_andcalibrate.ipynb** : Call the Fors2DataAcess::get_calibrationfactor(self,specname) function to obtain the multiplicative factor for the spectrum and plot it in the new units

## 5)  Calculate background on calibrated flux
- **AccessFors2Spectra_calculatebackground.ipynb**

## 6) Tool        
- **Factor_Magnitude.ipynb** : unimportant tool
