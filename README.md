# IT492_Pheonix_1

<h3>Datasets : https://datarepo.eng.ucsd.edu/mcauley_group/gdrive/googlelocal/review-Illinois.json.gz, https://datarepo.eng.ucsd.edu/mcauley_group/gdrive/googlelocal/meta-Illinois.json.gz </h3>

- This repository is about 'Google review' dataset for the state of Illinois, USA.The dataset is intended for use in Data visulization through EDA, data preprocessing, word2vec, bag of words, TF-IDF vectorization,classification,finding cosine similarities.The dataset files are in CSV(Comma Separated Value) format containing the data.

**Data Description :**
This project makes use of 2 datasets, reviews and the metadata. 
**Reviews** data contain the following columns:
**user_id** - ID of the reviewer
**name** - name of the reviwer
**time** - time of the review (unix time)
**rating** - rating of the business
**text** - text of the review
**pics** - pictures of the review
**resp** - business response to the review including unix time and text of the response
**gmap_id** - ID of the business

**Metadata** contains the following columns:
**name** - name of the business
**address** - address of the business
**gmap_id** - ID of the business
**description** - description of the business
**latitude** - latitude of the business
**longitude** - longitude of the business
**category** - category of the business
**avg_rating** - average rating of the business
**num_of_reviews** - number of reviews
**price** - price of the business
**hours** - open hours
**MISC** - MISC information
**state** - the current status of the business (e.g., permanently closed)
**relative_results** - relative businesses recommended by Google
**url** - URL of the business
 





<h2>EDA :</h2>
Exploratory Data Analysis (EDA) to gain insights into reviews, ratings and categories .
In EDA we provide data visualisation in different graph method like density plot, geographical scatter plot, column chart, data distribution plot, pie chart, heatmap. EDA summarize the main behaviour, features, and patterns in a dataset.
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




