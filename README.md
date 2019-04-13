# Linear-Regression-Model-Python3
Linear Regression Model (Python3) based on large oceanic dataset. (bottle.csv)

# Background Info
Dataset is LARGE (~864864 rows) for the problem is over 60 years of oceanic data obtained on https://www.kaggle.com/rtatman/datasets-for-regression-analysis
Problem to be solved from linear regression Is there a relationship between water salinity & water temperature? 
Can you predict the water temperature (y) based on salinity(x)? Target outcome water temp (ypred)

* Included a study based on density as well since multiple literatures explain to geta true idea in 
water temp and salinity relationship density must be accounted for as well

# Results Take Away:

Slope gives us the coefficient for our regression model.
The first slope value about 1.39 lets us know that as we increase salinity dependent on density temperature will
will increase on average ~1.4 units each time however we observe a negative relationship between
salinity and temperature when we don't account for density when factoring in salinity values. As we can see
my regression model correctly predicts this relationship. (see LR plot)

# Contour Plot Takeaway:

We can see as density increases and salinity decreases the colder the water temperature gets
However as we increase salinity and decrease density then we find that water temp increases.
