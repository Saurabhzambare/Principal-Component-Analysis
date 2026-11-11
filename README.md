# Principal Component Analysis practice

This notebook uses synthetic data for 100 features and 10 samples. The WT and KO labels identify the two simulated groups. No biological samples or experimental evidence are used.

Open [the notebook](Principal_Component_analysis.ipynb) in Jupyter with NumPy, pandas, matplotlib, and scikit-learn. Run the cells from the top. The data generation seeds both Python's random generator and NumPy with 42. In the checked environment, running the cell code twice reproduced the printed output.

The notebook transposes the input so each sample is a row, standardizes each feature, then fits PCA. The scree plot shows the share of variance explained by each component. The PC1/PC2 scatter plots the samples in two dimensions. Absolute PC1 loadings show which features contribute most strongly to that component. The sign of a principal component can flip without changing its meaning, and the simulated groups do not establish a biological finding.
