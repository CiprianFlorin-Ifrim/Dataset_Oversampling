######Imbalanced Dataset correction by using oversampling techniques such as SMOTE and ADASYN

Machine Learning Estimators expect a balanced amount of samples between all classes, however, that is not always the case. In order to correct this, we can use oversampling techniques.
Both methods use the K-Nearest Neighbors relation to create synthetic samples, while the ADASYN method also uses a density function to create more sparse samples.

Example of original dataset, oversampled with SMOTE/ADASYN, plotted with Plotly:
![Screenshot (1123)](https://user-images.githubusercontent.com/94687473/159691954-7fb5bc25-3e51-45d4-97fd-1466e526589a.png)
