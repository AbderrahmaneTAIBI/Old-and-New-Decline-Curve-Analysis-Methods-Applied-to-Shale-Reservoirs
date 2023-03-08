# Report: Reservoir Engineering Decline Curve Analysis (DCA) Comparisons

This Jupyter notebook compares the application of the old empirical method of Decline Curve Analysis (DCA) in Reservoir Engineering known as Arp's method with the recent Logistic Growth model. The comparison is based on the analysis of production data obtained from the dataset "HS01DataDCA.csv".

The notebook makes use of several libraries including:

scipy.optimize.curve_fit: Used to fit the production data to the different models
numpy: Used for numerical operations
pandas: Used for data manipulation and analysis
matplotlib.pyplot: Used for data visualization and plotting
seaborn: Used for enhanced data visualization and plotting
statsmodels.nonparametric.smoothers_lowess: Used to apply a Lowess smoother to the data

### Dataset
The dataset used in this analysis is "HS01DataDCA.csv" which contains production data for a reservoir. The data includes time, oil/Gas/Water, but since we are in a shale gas reservoir we only focus on Gas Production.

Note: All the data is from SPE open source data.

## Analysis
The notebook includes step-by-step explanations of the Arp's method and the Logistic Growth model, and how they can be applied to the dataset. The data is then plotted for both models and compared. Additionally, the mean squared error (MSE) and accuracy score are computed for both models to assess their performance. The analysis is enhanced with the use of Lowess smoothing, which is applied to the dataset and plotted for comparison.

## Conclusion
In conclusion, this Jupyter notebook provides a comparison of the traditional empirical Arp's method with the more recent Logistic Growth model for Decline Curve Analysis in Reservoir Engineering. The notebook provides an overview of the models and their application to the dataset, including the visualization of the data and the computation of the MSE and accuracy scores. The Lowess smoothing provides additional insights into the trends in the data. Overall, this notebook provides a useful resource for understanding the application of different DCA methods in Reservoir Engineering.
