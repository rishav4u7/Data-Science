
# Telecom Churn:

A telecom firm which has collected data of all its customers. The main types of attributes are:
- Demographics (age, gender etc.)
- Services availed (internet packs purchased, special offers taken etc.)
- Expenses (amount of recharge done per month etc.)

Based on all this past information, a model has to be build which will predict whether a particular customer will churn or not, i.e. whether they will switch to a different service provider or not. So the variable of interest, i.e. the target variable here is ‘Churn.  
- 1	= Customer Churned
- 0	= Customer not Churned




## Dataset Information

Link : [Dataset]( https://drive.google.com/drive/folders/1ri_rd9229ligu27r7Wh9zP5mdOGjtiUH?usp=sharing)

The above link contains three dataset which will be merged and be used for building a model using Logistic Regression.

Steps:
    
    1. Data cleaning and preparation
    2. Preprocessing steps
    3. Test-train split
    4. Feature scaling
    5. Model Building using RFE, p-values and VIFs
    6. Modal Evaluaion

## Result & Observation
As the dataset have 27% churn rate and seems to be imbalanced. Hence, the ROC curve is used here for examining the model efficiency.

In train dataset, the best possible AUC achieved is 0.85 at cutoff of 0.3.

![download](https://user-images.githubusercontent.com/34181629/152781856-c8578f3a-5b6e-4ecb-8794-9ab9107e6cec.png)![download](https://user-images.githubusercontent.com/34181629/152781890-893bed10-b8c8-4f35-9619-6c25a69e24a4.png)


In test dataset, the best possible AUC achieved is 0.83 at cutoff of 0.42.


![download](https://user-images.githubusercontent.com/34181629/152781910-fa08f0c3-a957-4c60-a5ba-050f1bd37db7.png)![download](https://user-images.githubusercontent.com/34181629/152781925-423ad102-c46d-4298-957c-f4baad4520e5.png)




## Software and Libraries

[Python 2.7 or Higher](https://www.python.org/downloads/)

[Numpy](https://pypi.org/project/numpy/)

[Matplotlib](https://pypi.org/project/matplotlib/)

[Pandas](https://pypi.org/project/pandas/)

[Jupyter Notebook](https://jupyter.org/install)

[Seaborn](https://pypi.org/project/seaborn/)

[Scikit-learn](https://pypi.org/project/sklearn/)

