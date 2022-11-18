# Home-Site-Quote-Conversion
Includes stacked models with class imbalance handling.
Most real life problems are imbalanced in the sense that you only have a small percentage of examples of one class (called the minority class), but a large percentage of examples of the other class (the majority class). For example, the minority class in a fraud detection problem is the fraud class. Correct prediction of the minority class is what matters the most in these problems. But since there only a few examples of the minority class, they are hard to find and separate out from the majority class. One of the ways to handle this class imbalance problem is to add synthetic (artificial) examples of the minority class in the region where you find them. It essentially amounts to populating a certain region with minority class examples so that the minority class has more visibility. A popular method for doing that is called SMOTE. This model makes use of SMOTE to overcome class imbalance.
Using an anonymized database of information on customer and sales activity, including property and coverage information, this model predicts which customers will purchase a given quote. Accurately predicting conversion would help better understand the impact of proposed pricing changes and maintain an ideal portfolio of customer segments. 
