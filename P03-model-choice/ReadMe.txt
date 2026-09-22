I would deploy **Linear Regression** because it achieved the lowest 5-fold cross-validated MAE of **2.03 ± 0.16 minutes**, compared with **2.69 ± 0.40** for the 50-tree Random Forest and **4.57 ± 0.18** for the depth-4 Decision Tree.
It also trains in milliseconds, requires almost no memory, and its coefficients make its predictions easy to explain to a restaurant owner.
The trade-off I accept is giving up the potentially greater flexibility of the Random Forest in exchange for **lower measured error, simpler deployment, faster training, and better interpretability** on this dataset.
