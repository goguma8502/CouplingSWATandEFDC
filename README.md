# CouplingSWATandEFDC
MATLAB script for coupling SWAT and EFDC (09/09/2018 Satbyeol Shin, University of Flordia)
 
The project named 'MATLAB script for coupling SWAT and EFDC' simulates an example of 2 upstream watersheds (named 'Yangdae river' and 'No-named River') using SWAT model and 1 downstream reservoir (named 'Ipjang reservoir') usnig EFDC model.

The SWAT models were set up to predict daily streamflow, soil erosion, and sediment transport of the Yang and NNM river watersheds separately. Then, each of the models was calibrated to streamflow and sediment observations made at the watershed outlets in 2017. The total number of parameter samples to be populated was set to 9600, and many parameter sets that gave equally good model performance were identified under the GLUE framework (Beven and Binley, 1992; Her and Chaubey, 2015; Her et al., 2015). In the following uncertainty analy-sis, a threshold NSE value of 0.8 was selected to quantify the equifinality of the calibration re-sults, based on the performance evaluation criteria suggested for watershed-scale modeling (Moriasi et al., 2015).

The EFDC model was configured to represent three-dimensional sediment movement in the Ipjang reservoir for a year, from January 1 to December 31, 2017 on a daily basis. The computa-tional time step was set to 1 second, considering the numerical stability and running time of the EFDC model, resulting in a 1-year sediment simulation taking approximately 4.5 hours to com-plete with a personal computer that has an Intel i7 8700k (3.70 GHz) processor and 32 GB Ran-dom Access Memory (RAM) under the Windows 10 operating system installed on a 256 GB Sol-id State Drive (SSD).
