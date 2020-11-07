# Daily Rainfall Analysis
Two files are attached which contain daily rainfall data over India for 2010 and 2011. Both of them contain a 357x122 matrix (XR1 and XR) an a binary vector (ZR1 and ZR). The matrices contain rainfall amounts at 357 locations over India, on each day during the monsoon seasons of 2010 and 2011 (122 days from 1 June to 30 September). ZR1 and ZR are binary vectors which classify every day as 'rainy" (1) or non-rainy (0) based on the rainfall across the landmass. <br />
1)Using a linear regression model to predict the rainfall XR(s,t) at any location 's' on day 't', using as predictor the rainfall at all other locations on the same day, and also rainfall at the same location on the previous 2 days. Using 2010 data for training. <br />
Building such a model for s=42 (Mumbai), s=158 (Delhi), s= 299 (Kharagpur) <br />
2)Using the same model to predict the rainfall at these 3 locations on each day of 2011.  Using values in XR as predictors. Comparing the results with the true values and compute error for 3 locations separately. <br />
3)Repeating the same process using LASSO linear regression. Using the coefficients, identified the top 5 predictors for each of the 3 locations. <br />
4)Using Decision Tree on 2010 data to classify each day as 1 or 0 (as given in ZR1). For each day, use the 357-dimensional rainfall vector as feature vector. Reported the 10 most discriminative features (i.e. locations) <br />
5)Using this Decision Tree to classify each day of 2011 as 1 or 0. Report accuracy by comparing with ZR. 
