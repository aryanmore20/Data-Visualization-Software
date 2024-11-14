# Data Visualization
Java Data Visualization project designed to make histogramming, plotting, and fitting accessible for Java users. 
## Features
- Histograms 1D/2D
- Functions 
- GraphErrors 
- Fitting routines using Minuit
- GUI tools for easily editing plot attributes and for fitting

1D and 2D Histograms :
Histograms represent data distribution by binning data points and plotting them as bars. In 1D histograms, the x-axis represents bins, and the y-axis represents frequency counts within each bin. 2D histograms extend this concept, using two axes (x, y) to represent two variables, with bin counts represented by color intensity or bar height.

Graph Errors : 
Histograms often include error bars to show statistical uncertainty. Common error types:
1. Poisson Errors: Typically used for counts in each bin, especially relevant when dealing with small data samples.
2. Systematic Errors: Can be incorporated if additional uncertainties are known.
3. GraphErrors: Tools or classes for adding and customizing error bars, useful in plotting and fitting.

Fitting Routines (Minuit) :
Fitting routines are used to find the parameters that best match a histogram to a model. Minuit is a commonly used minimization tool in scientific computing:
1. Likelihood and Chi-Square Fitting: Using Minuit for various fitting techniques (like least squares or maximum likelihood).
2. Parameter Optimization: Minuit can adjust parameters to minimize residuals or optimize the fit function.
3. Error Estimation: Includes functionality to calculate parameter uncertainties and error contours.

GUI Tools for Plotting and Fitting :
Interactive GUI tools simplify histogram plotting and fitting processes by providing options to modify attributes visually.
1. Attribute Editing: Customize colors, labels, and axis limits.
2. Fitting Interface: Interactive tools for selecting fit functions and adjusting fit parameters.
3. Real-time Plot Updates: View adjustments to fit and plot attributes instantly.

These features are often found in data analysis environments or specialized libraries like ROOT (for high-energy physics) or matplotlib (Python), which provide high-level interfaces for scientific plots and data visualization.






