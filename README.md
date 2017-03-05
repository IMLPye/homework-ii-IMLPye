1. Explain how you validated your model and why    
   I use R^2 to validate my model, which compare the predicated value and the true value of testing data.
   If the R^2 value is high, it means the predicated value and true value have big difference
   If the R^2 value is low, it means the predicated value and true value have small difference. Which means the prediction mdoel is good.

2. I claim my algorithm could have high accuracy with R^2 smaller than 0.3.

3. The model is based on linear regression for the prediction.

4. There are two files:
	1) homework2_rent.py with two functions: 
			- score_test: The code to download data, process, and return R^2
			- predict_rent: The code to build and validate model
	2) test_rent.py with a function test_rent to call the score_test in homework2_rent.py
