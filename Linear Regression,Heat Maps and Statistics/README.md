Q1: The Systolic Blood Pressure Data (X1, X2, X3) for each senior patient that visited
IIT Ropar Health Centre in the month of October 2019 is provided in the attached excel
sheet “IITHealthCentreData.xls” where, X1 = systolic blood pressure, X2 = age in years,
X3 = weight in kilograms.
1.1 Read data from the excel sheet directly in python and based on in-build functions
in python, use the multilinear regression to fit:

X1 = a0 + a1*X2 + a2*X3 + e

and compute the coefficients, the standard error of estimates, coefficient of variation and
correlation coefficients between X1, X2 and X3 (taught in class on 23/10/19).

1.2 Plot the obtained regression model in Q1.1 in 3D.

1.3 Recompute the regression in Q1.1 but use the matrix approach to compute the
coefficients, the standard error of estimates, coefficient of variation and correlation
coefficients between X1, X2 and X3. In addition, compute the 95% confidence
interval of coefficients using t<sub>α,2n-1</sub> statistics from the in-build function in python.
Mention the true relative error in coefficients, the standard error of estimates,
coefficient of variation and correlation coefficients obtained using matrix approach
where the true values can be taken as the one calculated using in-build functions in
python (in Q1.1).
