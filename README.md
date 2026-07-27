# Customer_churn_analysis
FINAL RESULTS SUMMARY
============================================================

Model                ROC-AUC      F1-Score     Accuracy     Precision    Recall      
--------------------------------------------------------------------------------
Decision Tree        0.4923       0.2424       0.6250       0.2857       0.2105      
Random Forest        0.5836       0.0000       0.7150       0.0000       0.0000      
XGBoost              0.5428       0.1667       0.6500       0.2593       0.1228      
Gradient Boosting    0.5280       0.0822       0.6650       0.1875       0.0526      

============================================================
RECOMMENDATIONS & INSIGHTS
============================================================


Best Performing Model: Random Forest

• ROC-AUC Score: 0.5836
• F1-Score: 0.0000
• Accuracy: 0.7150

Key Business Insights from Data:

• Customers with month-to-month contracts have the highest churn risk

• Churn is highest during first 12 months of customer tenure

• Electronic check payment method correlates with higher churn

• Customers without additional services (tech support, online security) churn more

• Senior citizens show different churn patterns than younger customers


Actionable Recommendations:

• Offer incentives for longer-term contracts

• Implement early retention programs for new customers (first year)

• Promote paperless billing & automatic payment methods

• Bundle services to increase customer stickiness

• Create targeted offers for high-risk segments


Analysis Complete! Check all generated visualizations in the Notebook.
