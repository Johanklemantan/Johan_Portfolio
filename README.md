# Johan_Portfolio
Johan's Data Science Portfolio 

# <a href='https://github.com/Johanklemantan/Shopee-Email-Campaign-Prediction'> Project 1 : Email Campaign Prediction</a><br>
- Create a classification model that able to save estiamtion budget for advertisement about 74% monthly to help marketing team send promotion advertisement only to customer who will likely to read it<br>
- Engineered features to help indentify the behaviour of the customer<br>
- Visualize the data using seaborn and matplotlib<br>
- Optimized the data using Linear Regression, Gaussian Naive Bayes, and Decision Tree Classifier Model, RepeatedStratifiedKFold, GridsearchCV, and threshold changing to reach best model<br>
- Deploy model for user using Flask

Results :  <br>
<img src='Project 1/result.PNG' width='750'><br>

# <a href='https://github.com/Johanklemantan/Delivery-Truck-Ontime-Delay-Prediction'> Project 2 : Delivery Truck On-Time / Delay Prediction</a><br>
- Create a model that able to predict whether the delivery will be delayed or on time <br>
- Decide top 10 factors that has the highest ratio to determine the delivery status. This is able to help business owner to focus on that 10 factors to reduce delay ratio <br>
- Optimized data using Gradient Booster Classifier, RepeatedStratifiedKFold and GridsearchCV to achieve best model with accuracy of 89% <br>

Top 10 factors that affecting delay of delivery : <br>
<img src='Project 1/FI.PNG' width='750'><br>

# <a href='https://github.com/Johanklemantan/Simple-Sentiment-Analysis-Predictor'> Project 3 : Sentiment Analysis Predictor </a> <br>
- Create a model that accept text input and able to classify whether the input is a positive or negative comment <br>
- Apply simple text preprocessing (lowercase, remove punctuation, stopwords, etc) <br>
- Optimized model with TfidfVectorizer and n-grams = 2 before applied with Logistic Regression and Multinomial Naive Bayes to receive up to 80% accuracy <br>
- Deploy model for user using Flask

Results :<br>
Positive Result :<br>
<p float="left">
  <img src='Project 1/Res3.PNG' width="450" />
  <img src='Project 1/Res4.PNG' width="450" /> 
</p> <br>
Negative Result :<br>
<p float="left">
  <img src='Project 1/Res1.PNG' width="450" />
  <img src='Project 1/Res2.PNG' width="450" /> 
</p> <br>

# <a href='https://github.com/Johanklemantan/Simple-Image-Classifier'> Project 4 : Animal Image Classifier</a><br>
- Create a model that able to differentiate picture between Cat, Dog, and Panda. This model could be useful for animal photographer who take picture of any animal<br>
- I was able to get the model to predict the animal with 73% accuracy after minimal tuning. For most of cases, this would meet the need of an end user of the app. To get these result, I used Sequential model with randomsearch of dense, droput, and added neuron number<br>
- I run this model in google colab with setting of runtime using GPU for time efficiency, also I can greed it out and use colorful picture<br>
Results :<br>
<img src='Project 1/Confusion Matrix.PNG' width='500'>
