# Ex03-Univariate-Analysis
# AIM
 To perform Univariate EDA on the given data set.
# EXPLANATION
 Exploratory data analysis is used to understand the messages within a dataset. This 
technique involves many iterative processes to ensure that the cleaned data is further sorted to 
better understand the useful meaning.The primary aim with exploratory analysis is to 
examine the data for distribution, outliers and anomalies to direct specific testing of your 
hypothesis.
# ALGORITHM
## STEP 1
Import the built libraries required to perform EDA and outlier removal.
## STEP 2
Read the given csv file
## STEP 3
Convert the file into a dataframe and get information of the data.
## STEP 4
Return the objects containing counts of unique values using (value_counts()).
## STEP 5
Plot the counts in the form of Histogram or Bar Graph.
## STEP 6
Use seaborn the bar graph comparison of data can be viewed.
## STEP 7
Save the final data set into the file

# CODE

import numpy as np

import pandas as pd

from scipy import stats

import seaborn as sns

df = pd.read_csv("/content/diabetes.csv")

df=pd.DataFrame(df)

df.head()

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/7f8608ae-c975-4334-9a6b-cca39423943a)

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/b567f544-abf7-45f4-91c3-f863697797e3)

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/e6da3bcc-cf49-45d5-a490-306e632bb4d5)

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/97da9a30-db60-456c-9a96-72c7fdd0366e)

# OUTPUT 

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/1172e035-9340-4af4-9414-e9bcb6208438)

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/97464b82-2baa-49ed-b7bb-b1c7867c4be2)

sns.distplot(df['Glucose'])

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/41f49479-2fa1-4496-bdac-25da185456f0)

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/b462eba4-03b4-4025-a171-1c96cb2ad73f)

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/2f5d51c4-0252-43fb-9569-938c463d2789)

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/6f9bf6a7-a5a7-4bd7-aea2-023e43b90e2e)

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/3dfd710f-ab84-4782-bdb5-a44e6d59bc5b)

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/e084c770-9f9b-44a4-94b7-fc639952994c)

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/94251920-2fdc-4fbd-bfcf-cc747b8ab810)

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/533cf474-1de4-47d3-9ab9-fc18f3c041d1)

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/c81332b3-f09b-455a-8bae-50c8220750c6)

![image](https://github.com/Rajasree-321/Ex03-Univariate-Analysis/assets/96918911/515781f5-b4f2-4e0e-be75-d4f2abd6a468)

# RESULT 
Thus the program to perform EDA on the given data set is successfully executed.



