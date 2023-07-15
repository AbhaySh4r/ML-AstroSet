# ML-AstroSet

Project1-Visuals.ipynb - Provides a high level overview of the data, with insights into what variables are relevant and how each stellar object is classified with the relevant attributes. 

LRandSVM.ipynb - Execution of Logistic Regression and Support Vector Machine classification using a linear kernal and Stochiastic Gradient Descent since the initial dataset is very large. Alternative approaches include subsampling to create a smaller representative sample of the dataset to run a SVM classification on, smaller sample was further processed with PCA. 

KNN_SVR_Class&Reg.ipynb - Classification and Regression process. Initially begin with NearestCentroid approach, but due to data limitations the performance was subpar, so we were forced to switch to using (K-Nearest Neighbors)KNN for a stronger classifier. Classification was done on the class variable to predict on a test set to visualize performance. Regression was performed using Support Vector Regression, scaling the data, and one-hot encoding the class variable to build a model for the redshift parameter. From this regression model, we found that as redshift increases (or the distance of each stellar object increases from us) that the luminosity of the red/infrared wavelength increases and green wavelengths decrease, which mirrors what we intuitively expect from the Doppler shifts. Additionally, we saw that as redshift increased, the model saw less Galaxies and Stars, and more Quasars, which made sense given that Quasars are some of the brightest objects in a stellar scan, often regardless of distance.

./data - holds the stellar dataset

./images - holds images

