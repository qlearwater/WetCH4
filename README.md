This deposit is associated with a manuscript submitted to Earth System Science Data, which includes scripts to model and upscale wetland methane fluxes along with example data.
The scripts were developed under Python 3 in Jupyter Notebook. 
The file 'WetCH4_model.ipynb' trains and validates random forest models with an example of eddy covariance data stored in flux_data.csv, and exports predictions and test metrics to output csv files.
The file 'WetCH4_upscale.ipynb' applies bootstrap models to upscale CH4 flux intensities from northern wetlands with example inputs from MERRA2, MODIS NBAR, SMAP, and topographic data. The output fluxes are stored in the 'Upscale' folder.
