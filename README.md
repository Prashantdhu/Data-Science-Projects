**INTRODUCTION** 

In Canada the health services are provided at no cost because it is covered and funded by the government. The system is called “Universal Health Care System” and was passed by legislation in 1984 under the Canada Health Act. However, the same does not apply for our neighboring country, the United States. The health services in the United States are mostly private and unlike Canada the people in the States have to pay for their health service fees. Due to the privatization of the healthcare system in the United States there is a competition within the industry to provide better services which makes it expensive for the people to afford. Therefore, health insurance companies play a huge role as they cover the cost of health services in exchange for an insurance premium. By purchasing health insurance people protect themselves from any future uncertainties and a huge debt. In order for the insurance companies to cover the cost of health services they must analyze how much premium to charge for each person. Every person has different day to day habits and can vary in their lifestyle choices which impacts how the insurance companies charge their premiums. 

The objective for this project is to develop the best model in predicting insurance premiums based on several factors using multiple linear regression. In order to predict the insurance premiums we first must determine which predictor variables are significant and develop a model with predictors that explains a high variability in terms of the premiums charged.This topic is very important as people residing in Canada can use this model to predict the insurance premiums they will be charged according to their personal information if they ever plan on moving to the United States.
The motivation for our study is to find the factor that most influences insurance price and help people plan accordingly to reduce their financial burden of paying high premiums. We will be using multiple linear regression to address this query.


**DATASET**

In order to answer our research topic we have acquired a dataset that has 7 variables and 1338 observations. The dataset contains both numerical and categorical values. The dataset is clean and no further cleaning is required. The variables are explained below according to the source of the dataset: 

Response Variable: 
Charges: Insured individual medical annual costs billed by the health insurance in USD($) . (Quantitative)

Predictor Variables: 
Age: Age of the primary Insured. (Quantitative)
Sex: Insured gender “Male or Female”. (Qualitative)
BMI: Body Mass Index. (Quantitative)
Children: Insured number of dependents. (Quantitative)
Smoker: Insured smoking habits “Yes or No”. (Qualitative)
Region: Insured region of residence “Southwest”,”Southeast”, “Northwest”, “Northeast”. (Qualitative)
 The dataset was acquired through Kaggle website and is an open sourced data licensed under “Open Data Commons”. [https://www.kaggle.com/datasets/mirichoi0218/insurance/] 
