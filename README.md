# Credit-Risk-Modelling
Evolving Credit Risk Models: Leveraging Bio-inspired Algorithms and Explainable AI for Loan Approval

  Basel II norms necessitate the banks to maintain a Capital Adequacy Ratio(CAR)of 8% of risk-weighted assets. This means banks have to allocate £8 in their reserve
for every £100 they risk to being default. The higher the risk the larger the money allocation for hedging the risk, which means less money is left for investments leading to lesser
profit to the banks. Credit Risk Modelling is a machine learning technique to quantify the risk of the borrower using their personal and credit information. This not only helps
banks in risk mitigation but also helps consumers in getting loans at cheaper rates. The dataset employed in this study was acquired from Lending Club, a prominent P2P lending
platform based in the United States.
The traditional machine-learning model focused on linear models for classificationbecause of their interpretability at the expense of accuracy. This study explores the field
of Genetic Algorithms(GA) for the reduction of dimension and model complexity. GA helped reduce the features from 142 in the original dataset to 17. A deep learning model
was deployed on the reduced data matrix to achieve an accuracy of 91% and recall for default loans of 90% for binary classification. The Loss Given Default(LGD) was reduced
from $234 million for Logistic Regression to $124 million for the deep learning model. Lack of transparency is one of the major challenges with the deep learning model often
described as a ’black box’ making it impossible to detect bias and enforce accountability. LIME and SHAP explanation tools are used to overcome the adversities of the deep
learning model. Effective utilization of such tools can help build a fair and transparent lending ecosystem.
