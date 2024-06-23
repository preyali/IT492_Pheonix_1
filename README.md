# Content based Filtering on Google Reviews Data

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


   
  
<h2>Data Preprocessing and Transformation :</h2>
Data preprocessing and transformation involve cleaning, organizing, and structuring raw data to make it suitable for analysis or model training.
Data preprocessing is the initial step in data preparation, where the raw data is cleaned and prepared for further analysis. We used the metadata and the content column as our corpus and did our preprocessing on it. We make use of stemming/lemmetization, tokenization, removal of stopwords in the process.
The data cleaning was also done based on our requirement for the project that was about content based filtering.
Content-based filtering uses item features to recommend other items similar to what the user likes, based on their previous actions or explicit feedback. The features here are categories of the reviews of the Google Review dataset.

We tried to apply bag of words and TF-IDF to find cosine similarities to find the most similar item to the one user wanted. We tried to map it to the user reviews so that the recommendation is best show for the user interest.
 





 <h2>Classification model building and Model evaluation : </h2>
		Building a classification model involves several key steps, such as model selection and evalution.
We used Word2vec, in classification, to provide user preffered recommendation using user’s past reviews, i.e if the user didn’t like something in the past, it won’t be recommended again to them. Word2vec is a continuous bag of words model, that predicts the middle words based on the surrounding context words. Its continuous skip-gram model predicts words within a certain range before and after the current word. (context window)


Model evaluation is a process to find the prediction of the trained model on the testing dataset or new, unseen data.
The model's performance can be evaluated by evaluation metrices such as Mean Absolute Error, Mean Squared Error, Root Mean Squared Error, etc.
We found the MSE to be 1.20 and MAE to be 0.79



<h2>Unique selling point of theproject </h2>
   A unique selling point (USP), also called a unique selling proposition, is the essence of what makes your product or service better than competitors. The USP of this project is the map integration, by finding the top  most similar places of the keywords and showing those places on the map. 












<h2> Contributors ✨ </h2>
<table>
    <tbody>
     <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/KrishRupapara"><img src="https://avatars.githubusercontent.com/u/94665286?v=4" width="100px;" alt="KrishRupapara"/><br /><sub><b>KrishRupapara</b></sub></a><br /></td>  
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/kir1906"><img src="https://avatars.githubusercontent.com/u/137956777?v=4" width="100px;" alt="kir1906"/><br /><sub><b>kir1906</b></sub></a><br /></td> 
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/asma-2922"><img src="https://avatars.githubusercontent.com/u/137956777?v=4" width="100px;" alt=""/><br /><sub><b>asma-2922</b></sub></a><br /></td>    
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/preyali"><img src="https://avatars.githubusercontent.com/u/137956777?v=4" width="100px;" alt=""/><br /><sub><b>preyali</b></sub></a><br /></td>    
      
    </tr>
  </tbody>
</table>

