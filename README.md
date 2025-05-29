# TASK--3
  Linear Regression - Housing Price Prediction


## 🚀 Objective

Implement and understand **simple & multiple linear regression** using:
- Scikit-learn
- Pandas
- Matplotlib

## 🧰 Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

### Preprocessing

- Encoded categorical variables using integer mapping.
- Removed the target column `price` from features.
- Split data into training and testing subsets (80-20).

## Model Evaluation

Model was trained using 'LinearRegression()' from 'sklearn'.

Evaluation metrics used:
- **MAE**: Mean Absolute Error
- **MSE**: Mean Squared Error
- **RMSE**: Root Mean Squared Error
- **R² Score**: Coefficient of Determination

## Visualization
  A scatter plot compares **actual prices** with **predicted prices**. The red diagonal line indicates perfect prediction.

## Output

First 5 rows of the dataset:
      price  area  bedrooms  bathrooms  stories mainroad guestroom basement  \
0  13300000  7420         4          2        3      yes        no       no   
1  12250000  8960         4          4        4      yes        no       no   
2  12250000  9960         3          2        2      yes        no      yes   
3  12215000  7500         4          2        2      yes        no      yes   
4  11410000  7420         4          1        2      yes       yes      yes   

  hotwaterheating airconditioning  parking prefarea furnishingstatus  
0              no             yes        2      yes        furnished  
1              no             yes        3       no        furnished  
2              no              no        2      yes   semi-furnished  
3              no             yes        3      yes        furnished  
4              no             yes        2       no        furnished  

Model Evaluation Metrics:
MAE: 979679.6912959901
MSE: 1771751116594.0352
RMSE: 1331071.4167895108
R² Score: 0.6494754192267803

![Screenshot 2025-05-29 160137](https://github.com/user-attachments/assets/7bfc6c17-4db3-4eac-8888-e0659b07d32a)

Model Coefficients:
                   Coefficient
area              2.358488e+02
bedrooms          7.857449e+04
bathrooms         1.097117e+06
stories           4.062232e+05
mainroad          3.668242e+05
guestroom         2.331468e+05
basement          3.931598e+05
hotwaterheating   6.878813e+05
airconditioning   7.855506e+05
parking           2.257565e+05
prefarea          6.299017e+05
furnishingstatus  2.103971e+05
