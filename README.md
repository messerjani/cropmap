Script to derive and apply crop classification based on Sentinel 1 satellite radar images in Google Earth Engine platform

For the derivation of crop maps a method has been developed with which time series crop information can be predicted based on remote sensing data. The training of the crop classification model has been performed on the cropland data of the LUCAS Land Use / Cover Area Frame Survey of year 2015 and 2018 – revised by d’Andrimont et al. (2020) – merged with the Sentinel-1A and -1B satellite radar images based on d’Andrimont et al. (2021). The pixel based crop classification has been derived using a random forest algorithm on Google Earth Engine platform. The method can be applied for 2015 and all following years. By adding a map of field boundaries the pixel based prediction can be overwritten by the majority of the predicted crop.

References:
d’Andrimont, R., Verhegghen, A., Lemoine, G., Kempeneers, P., Meroni, M. & van der Velde, M. 2021. From parcel to continental scale – A first European crop type map based on Sentinel-1 and LUCAS Copernicus in-situ observations. Remote Sensing of Environment, 266.
d’Andrimont, R., Yordanov, M., Martinez-Sanchez, L., Eiselt, B., Palmieri, A., Dominici, P., Gallego, J., Reuter, H.I., Joebges, C., Lemoine, G. & van der Velde, M. 2020. Harmonised LUCAS in-situ land cover and use database for field surveys from 2006 to 2018 in the European Union. Scientific Data, 7, 1–15.
