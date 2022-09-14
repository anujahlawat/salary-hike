#### statsmodels|sklearn|matplotlib|pandas|numpy
#### ols|LinearRegression|LeaveOneOut|Kfold|train_test_split

**Task :** build a simple linear regression model to predict salary using experience

**Summary :** 
I build a simple linear regression model using :
+ ols method
+ LinearRegression

I used ols to understand some basic terms like R-squared, adj. R-squared,  AIC, significance of p-value. 
Further I build model using LinearRegression. The techniques I used in building model are - LeaveOneOut, Kfold, train_test_split to compare all these with the same dataset.

**Conclusion :**
+ Model build using ols has R-squared = 95% which is good and LinearRegression have accuracy approximately in the line of 90's.
+ All the three techniues - LeaveOneOut, Kfold, train_test_split give approximately same accuracy except LeaveOneOut (60%) and this might be due to very small dataset I choose to build model.
