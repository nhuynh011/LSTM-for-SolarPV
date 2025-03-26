# LSTM-for-SolarPV
For research on prediction of Solar PV generation with weather data using LSTM-based cGAN. Currently incomplete and will not run.

# Content
**ModelEvaluation.ipynb**: Includes evaluation metrics of this model on unseen data, correlation graphs, and an outline of the cGAN Generator and Discriminator architecture. All code regarding architecture and some data has been removed for privacy reasons.<br/>
**MetaDis.pth**: The trained discriminator with current epochs, optimizer state, loss, and learning rate scheduler state.<br/>
**MetaGen.pth**: The trained generator with current epochs, optimizer state, loss, and learning rate scheduler state.<br/>

# Credit
cGAN and LSTM structure implimented by PhD lab member. I fixed the input/output to be suitible for a slightly different application and optimized some hyperparameters.
 
