# Machine-Learning-Logit-Project
This repository contains the project for Machine Learning course to obtain the Data Analytics diploma.

## Code sample
```Azure Machine Learning Studio
select * ,
       1- Avg_Open_To_Buy as inv_OpenToBuy,
       power (Credit_Limit,2) as sq_CreditLimit,
       power (Total_Revolving_Bal,2) as sq_TotalRevolving,
       power (Avg_Open_To_Buy,2) as sq_OpenToBuy,
       power (Credit_Limit,3) as cu_CreditLimit,
       power (Total_Revolving_Bal,3) as cu_TotalRevolving,
       power (Avg_Open_To_Buy,3) as cu_OpenToBuy
from t1;
```

## Result sample

<img align="left" alt="JPG" src="https://user-images.githubusercontent.com/98499583/151719309-d732e34d-c0e4-4d67-9e18-3ec91ca58f10.JPG" width="40%" height="auto" />
