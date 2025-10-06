I wrote this paper in the context of my Econometrics I class at Paris Dauphine - PSL University, in April of 2024.

gretl code

(french language)

It aims at explaining the 3pt shooting percentage of NBA (National Basketball Association) players.

The explaining variables studied are the following:

minutes played average distance of attempted shots

I proceeded to an OLS estimation, with model significance and coefficient tests. I used Chow (variable stability) and variable addition tests.

PART 1 CONCLUSION::

minutes played as well as average distance of attempted shots are both significant to explain 3pt shooting percentages. In the process, I also considered player position (guards, forwards, centers) as well as percentage of shots taken in the corner. Those 2 variables did not improve the model explicative power.

#######################################################################################

In the second part of my paper (file : ODENCH1.pdf), we look for improvements to the original regression model.

Different combinations of variables are tested to find the best one. However, the optimal model remains the one including minutes played and shot distance.

Autocorrelation of errors is checked using Durbin-Watson and Breusch-Godfrey tests. Both tests show no autocorrelation.

Heteroskedasticity is then tested with Goldfeld-Quandt and White tests. Both tests reject the assumption of homoskedasticity. To fix this, I applied a quasi-difference correction for autocorrelation. Then, a weighted least squares regression corrects for heteroskedasticity. After correction, coefficients remain stable and significant.

The distance of the shots increases success, while minutes slightly reduce it.

PART 2 CONCLUSION::

the corrected model is valid and could include more variables later.
