# ML-QSTP-19
Problems encountered - 
1. Simple Syntax errors because of unfamiliarity with Python.
2. I was stuck on Gradient Descent for the Univariate Linear Regression, got mutiple errors there like double scalar overflow and then the gradient descent converged but didn't give me the right answer. I finally used numpy.subtract instead of normal subraction with matrix elements and changed the value of alpha and no. of iterations, so the code started working automatically without giving me an overflow error. Although i did dolve the problem,still not sure what really went wrong previously.
Note : I have added a snippet in the notebook to print the list J_history so that you can directly see that Grdient Descent converges(change is less than 10^-3)
