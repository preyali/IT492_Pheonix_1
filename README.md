# IT492_Pheonix_1

<h3>Dataset : https://www.kaggle.com/datasets/sooyoungher/smoking-drinking-dataset/data </h3>

- This repository is about Smoking and Drinking dataset.The dataset is intended for use in Data visulization through EDA, data preprocessing, transformation, corelation, data split, hyperparameter and the model selection.The dataset file is in CSV(Comma Separated Value) format containing the data.

**Data Description :**
1. **sex:** indicates the gender of the individual, male or female.

2. **age:** age was categorised into 5-year intervals, i.e., 20–24 years, 25–29 years, and 85+ years. These intervals were then converted into numeric values by taking the lower bound of the interval.

3. **height:** indicates the height of the individual (rounded up to 5cm).

4. **weight:** indicates the weight of the individual (rounded up to 5kg).

5. **waistline:** indicates the circumference of the individual's waist.

6. **sight_left:** represents the visual acuity of the individual's left eye. Visual acuity measures the ability of the eye to distinguish shapes and object details at a given distance. This ranges from 0.1 to 2.5, with values < 0.1 being shifted up to 0.1.

7. **sight_right:** represents the visual acuity of the individual's right eye.

8. **hear_left:** evaluates the person's left ear's hearing, assigning a 1 to any abnormal hearing and a 2 to normal hearing.

9. **hear_right:** evaluates a person's right ear hearing using the same categorization scheme as hear_left.

10. **SBP (Systolic blood pressure):** determines the person's maximum systolic blood pressure, expressed in millimeters of mercury (mmHg). The pressure in the arteries during a heartbeat is measured by the systolic blood pressure.

11. **DBP (Diastolic blood pressure):** determines the person's diastolic blood pressure, expressed in millimeters of mercury (mmHg). The pressure in the arteries during the period between heartbeats is measured by diastolic blood pressure. The source mentioned above.

12. **BLDS:** measures the individual's fasting blood glucose in mg/dL. This represents the concentration of glucose per 100 ml of blood prior to eating a meal.

13. **tot_chole:** measures the total concentration of (ester and non-ester) cholestorol in the individual, in mg/dL.

14. **HDL_chole:** calculates the total cholesterol concentration in a person's HDL (high density lipoprotein) region, expressed in milligrams per deciliter. Good cholesterol, or HDL cholesterol, is a type of cholesterol that returns to the liver after being absorbed from the blood and eliminated. Keep in mind that having higher HDL cholesterol can reduce your risk of heart disease.

15. **LDL_chole:** quantifies the total cholesterol concentration in the LDL (low density lipoprotein) region in milligrams per deciliter. The majority of the cholesterol in the body is LDL cholesterol, sometimes referred to as bad cholesterol. Elevated levels of this may increase the risk of stroke and heart disease.

16. **triglyceride:** calculates the blood's total triglyceride content, expressed in milligrams per deciliter. One kind of lipid, or fat, that moves through our bloodstream is triglycerides, which are typically derived from the food we eat.

17. **hemoglobin:** measures the total concentration of hemoglobin in the individual's blood, in g/dL. Hemoglobin is a protein in our red blood cells that carries oxygen.

18. **urine_protein:** determines the person's urine's protein content. Elevated protein levels in the urine, also known as proteinuria, may indicate a number of health issues, including renal and heart failure. supply. The label encodings for this variate ( 1(-), 2(+/-), 3(+1), 4(+2), 5(+3), and 6(+4) ) are not clear. However, we could surmise that they represent the number of standard deviations the value in the feature distribution resides at from the mean.

19. **serum_creatin:** measures the concentration of creatinine in the individual's serum (which resides in their blood), in mg/dL. Creatinine is a waste product of creatine, which is produced to supply energy mainly to the muscles. Usually, this is removed entirely by your kidneys. Thus, if kidney function is abnormal, the concentration of creatinine will increase.

20. **SGOT_AST:** measures the SGOT (glutamate-oxaloacetate transaminase) and AST (aspartate transaminase) values in IU/L, which are values in blood tests that quantify liver, heart and other organs' performance. In particular, when these are damaged, their value goes up. Normal values are around 0–40 IU/L.

21. **SGOT_ALT:** Doctors use SGOT (glutamate-oxaloacetate transaminase) and ALT (alanine transaminase) values in blood tests to see how well the liver is working. In particular, when it is damaged, its value goes up. Normal values are around 0–40 IU/L.

22. **gamma_GTP:** determines the gamma-GTP (y-glutamyl transpeptidase) value in IU/L, which is a bile dict value that indicates liver function. For men, the normal range is 11–63 IU/L, and for women, it is 8–35 IU/L.

23. **SMK_STAT_TYPE_CD:** measures the individual's smoking state, where 1 corresponds to them never smoking, 2 corresponds to them having used to smoke but quit, and 3 corresponds to them still smoking.

24. **DRK_YN:** is a flag that indicates whether the individual is a drinker or not.

<h2>EDA :</h2>
Exploratory Data Analysis (EDA) to gain insights into diamond characteristics.
In EDA we provide data visualisation in different graph method like pair plot, cat plot, subplot, data distribution plot, pie chart, scatter plot. EDA summarize the main behaviour, features, and patterns in a dataset.
Describing the relation between each other and making the observations.

<h2> Contributors ✨ </h2>

  <table>
  <tbody>
    <tr> 
      <br>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/hetpatel25"><img src="https://avatars.githubusercontent.com/u/109530217?v=4" width="100px;" alt="HetPatel"/><br /><sub><b>hetpatel25</b></sub></a><br /></td>            
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/utsavmaru"><img src="https://avatars.githubusercontent.com/u/92310851?v=4" width="100px;" alt="UtsavMaru"/><br /><sub><b>utsavmaru</b></sub></a><br /> </td>
    </tr>
  </tbody>
  </table>  
<h2>Data Preprocessing and Transformation :</h2>
Data preprocessing and transformation involve cleaning, organizing, and structuring raw data to make it suitable for analysis or model training.
Data preprocessing is the initial step in data preparation, where the raw data is cleaned and prepared for further analysis.
This step involves several tasks: Data transformation involves converting data into a different format or structure to meet the requirements of specific analysis techniques or machine learning algorithms

<h2> Contributors ✨ </h2>

<table>
  <tbody>
      <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/dhyeyladani24"><img src="https://avatars.githubusercontent.com/u/141909435?v=4" width="100px;" alt=" DhyeyLadani"/><br /><sub><b>dhyeyladani24</b></sub></a><br /></td>
      </tr>
  </tbody>
</table>

 <h2>Classification model building, Hyperparameter Tuning and Model evaluation : </h2>
Building a classification model involves several key steps, such as model selection, hyperparameter tuning and model evaluation.
There are many regression model available to use, they can selected based on the nature of the problem.
Such models are, Logistic Regression, Desicion Tree, KNN, NN, Random Forest, Catboost,etc.
Hyperparameters are configuration settings for the classification algorithm
Yechniques like grid search or randomized search can be used find the best combination of hyperparameters that optimize the model's performance.
Cross-validation assess how well the model generalizes to unseen data at each combination of hyperparameters.
Model evaluation is a process to find the prediction of the trained model on the testing dataset or new, unseen data.
The model's performance can be evaluated by evaluation metrices such as Mean Absolute Error, Mean Squared Error, Root Mean Squared Error, etc.

<h2> Contributors ✨ </h2>
<table>
    <tbody>
     <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/KrishRupapara"><img src="https://avatars.githubusercontent.com/u/94665286?v=4" width="100px;" alt="KrishRupapara"/><br /><sub><b>KrishRupapara</b></sub></a><br /></td>  
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/kir1906"><img src="https://avatars.githubusercontent.com/u/137956777?v=4" width="100px;" alt="kir1906"/><br /><sub><b>kir1906</b></sub></a><br /></td>                 
    </tr>
  </tbody>
</table>


<h2>T2 Identified list classification problems :</h2>
<b> Alcohol Consumption: </b>
<br>
Binary classification: Predict whether an individual is a drinker (1) or not (0) based on factors like weekly alcohol intake.
<br>

<b> Smoking Status: </b>
<br>
Binary classification: Predict whether an individual is a non-smoker (1) or used to smoke but quit (2) or still smoking (3) based on attributes such as 'age', 'sex', 'SBP' (systolic blood pressure), and 'DBP' (diastolic blood pressure). This is interesting as it can help in understanding the relationship between smoking and various health indicators like blood pressure.
<br>

<b> Liver Function and Enzyme Levels: </b>
<br>
Binary classification: Predict whether an individual has abnormal liver function (1) or normal liver function (0) based on attributes like 'SGOT_AST', 'SGOT_ALT', and 'gamma_GTP'. This could be interesting for understanding the relationship between liver health and lifestyle factors.
<br>

<b> Health Risk Assessment: </b>
<br>
Binary classification: Predict whether an individual is at high risk (1) or low risk (0) of health issues based on a combination of attributes such as 'age', 'sex', 'SBP', 'DBP', 'hemoglobin', 'cholesterol' levels, and smoking and drinking habits. This is a complex problem but could be the most interesting as it involves multiple health-related attributes and behaviors.
<br>

<b> Sight and Hearing Problems: </b>
<br>
Binary classification: Predict whether an individual has sight or hearing impairment (1) or not (0) based on 'sight_left', 'sight_right', 'hear_left', and 'hear_right' attributes. This problem can help in assessing the impact of smoking and drinking on sensory health.
<br>

<h2> Which one does seem the most interesting to you and why? </h2>
<h4>
Among all given classification problems prediction of "Alcohol consumption" and "Smoking status" seems most interesting. The reason these problems are intriguing is because they are directly related to common lifestyle choices and habits that have significant implications for public health and individual well-being. Alcohol consumption is a widespread behavior with varying levels of consumption, and it is associated with various health outcomes. Smoking is a well-documented health risk factor, and understanding its prevalence is vital for public health initiatives.
</h4>




