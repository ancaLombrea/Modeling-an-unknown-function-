# MODELING AN UNKNOWN FUNCTION USING LINEAR REGRESSION METHOD

Given a set of input-output data, where the output is generated by an unknown, but static, non-linear function. The output is affected by noise, which we assume to be additive, Gaussian, and zero-mean. The function has two input variables and one output variable. A model needs to be developed for this function using a polynomial approximator. A second dataset, generated by the same function, is provided for validating the developed model. Both sets are provided in a MATLAB data file, each containing a structure for each set. 

Requirements:
Program a polynomial approximator with a configurable degree. Try training approximators of various degrees to obtain the most accurate one. Validation must be performed continuously on the different validation dataset (including comparing different values of m, for example). Report the mean squared error on both datasets (identification and validation) and graphically represent the result given by the approximator compared to the actual values of the function on both datasets.
