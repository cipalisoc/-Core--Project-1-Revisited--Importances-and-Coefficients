# (Core) Project 1 Revisited: Importances and Coefficients
![coeff](https://github.com/cipalisoc/-Core--Project-1-Revisited--Importances-and-Coefficients/blob/main/coeffs.png?raw=true)

Based on the above plot, the most impactful features are 'Outlet_Identifier_OUT049', 'Outlet_Identifier_OUT035', and 'Outlet_Size'. What this means is that for every 1 point increase in 'Outlet_Size', the predicted sales price decreases by -1.377442e+14. For every 1 point increase in 'Outlet_Identifier_OUT035', the sales price decreases by -7.648520e+13. Lastly, for every 1 point increase in 'Outlet_Identifier_OUT049', the predicted sales price increases by 8.359209e+13.

![imports](https://github.com/cipalisoc/-Core--Project-1-Revisited--Importances-and-Coefficients/blob/main/features.png?raw=true)

The above plot depicts the top 5 most important features in predicting price in our random forest model with the 'Item_MRP' being the most important.

![shapbar](https://github.com/cipalisoc/-Core--Project-1-Revisited--Importances-and-Coefficients/blob/main/shap_bar.png?raw=true)

Between the shap summary plot and the feature importances plots above, the top two features ('Item_MRP' and 'Outlet_Type_Grocery_Store') were the top two. While 'Item_Visibility' and 'Outlet_Identifier_OUT27' were common in both plots, they were not in the same order, and 'Item_Weight' was in the top 5 most important features, but was in seventh in the shap summary plot.

![shapdot](https://github.com/cipalisoc/-Core--Project-1-Revisited--Importances-and-Coefficients/blob/main/shap_dot.png?raw=true)

The dot plot of the shap summary above shows that 'Item_MRP', 'Outlet_Type_Grocery_Store', and 'Outlet_Identifier_OUT27' were the top three features that explained price prediction the most. For 'Item_MRP' the higher this value, the more it added to the predicted price. For 'Outlet_Type_Grocery_Store', the higher this value, the more it decreased price in price prediction. For 'Outlet_Identifier_OUT27', the higher this value, the more it added to price in price prediction.
