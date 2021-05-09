# Johan_Portfolio
Johan's Data Science Portfolio <br>
These are some projects that I've been working on since I was graduated from Purwadhika Bootcamp School in March 2021

## <a href='https://github.com/Johanklemantan/Shopee-Email-Campaign-Prediction'> Project 1 : Email Campaign Prediction</a><br>
- Create a classification model that able to save estiamtion budget for advertisement about 74% monthly to help marketing team send promotion advertisement only to customer who will likely to read it<br>
- Engineered features to help indentify the behaviour of the customer<br>
- Visualize the data using seaborn and matplotlib<br>
- Optimized the data using Linear Regression, Gaussian Naive Bayes, and Decision Tree Classifier Model, RepeatedStratifiedKFold, GridsearchCV, and threshold changing to reach best model<br>
- Deploy model for user using Flask

Results :  <br>
<img src='Project 1/result.PNG' width='750'><br>

## <a href='https://github.com/Johanklemantan/Delivery-Truck-Ontime-Delay-Prediction'> Project 2 : Delivery Truck On-Time / Delay Prediction</a><br>
- Create a model that able to predict whether the delivery will be delayed or on time <br>
- Decide top 10 factors that has the highest ratio to determine the delivery status. This is able to help business owner to focus on that 10 factors to reduce delay ratio <br>
- Optimized data using Gradient Booster Classifier, RepeatedStratifiedKFold and GridsearchCV to achieve best model with accuracy of 89% <br>

Top 10 factors that affecting delay of delivery : <br>
<img src='Project 1/FI.PNG' width='750'><br>

## <a href='https://github.com/Johanklemantan/Simple-Sentiment-Analysis-Predictor'> Project 3 : Sentiment Analysis Predictor </a> <br>
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

## <a href='https://github.com/Johanklemantan/Simple-Image-Classifier'> Project 4 : Animal Image Classifier</a><br>
- Create a model that able to differentiate picture between Cat, Dog, and Panda. This model could be useful for animal photographer who take picture of any animal<br>
- I was able to get the model to predict the animal with 73% accuracy after minimal tuning. For most of cases, this would meet the need of an end user of the app. To get these result, I used Sequential model with randomsearch of dense, droput, and added neuron number<br>
- I run this model in google colab with setting of runtime using GPU for time efficiency, also I can greed it out and use colorful picture<br>
Results :<br>
<img src='Project 1/Confusion Matrix.PNG' width='500'>

## <a href='https://github.com/Johanklemantan/Simple-Text-Summarizer'> Project 5 : Text Summarizer</a><br>
- Create a model using NLP-Spacy that able to summarize the input English based language article into important sentences inside it <br>
- Summary was taken from sentences by weighting every words of sentences and take the top n importance sentences as a summary <br>
- This model able to help people who does not have a lot of time for reading all the article and just want to get into the point of their article <br>
- Deploy the model using heroku for better user experience <br>
Results : <br>

You can try to summarize an article <a href='https://jo-text-summarization.herokuapp.com/'>here</a> : <br>
Result : <br><br>
<img src='Project 1/hasil1.png'/><br>

## <a href='https://github.com/Johanklemantan/Dota-2-Hero-Base-Stat-Visualization'> Project 6 : Dota 2 Base Stat Visualization using Tableau </a><br>
- Visualize the base stat of Dota 2 hero on updated patch 7.29 (Dawnbreaker included). This visualization is useful for someone who loves and play Dota 2 to choose best hero stat in order to enhance their laning stage and boosting their chance to win the game<br>
- Scrap the data from <a href='https://dota2.fandom.com/wiki/Dota_2_Wiki'>Dota 2 Fandom</a> using Selenium<br>
- Clean the data to make easier to visualize using pandas<br>
- Visualize the data using Tableau<br>
Results : <br>
<img src='Project 1/result4.PNG'><br>
Check my tableau post in here : <a href='https://public.tableau.com/profile/johan.klemantan.widagdo#!/vizhome/Dota27_29HeroBaseStat/Story1'>Dota 2 Hero Base Stat Visualization </a>

## <a href='https://github.com/Johanklemantan/LinkedIn-Job-Vacancy-Web-Scraping'> Project 7 : Scraping Job Vacancy in Data Industry from LinkedIn </a><br>
- Visualize the condition of what job in data industry that company is looking for. This visualization is useful for someone who is looking for a job in Data Industry and want to see the situation <br>
- Scrap the data from <a href='https://linkedin.com'>LinkedIn</a> using Selenium<br>
- Clean the data using pandas<br>
- Visualize the data using Tableau <br>
Results :<br>
<img src='Project 1/Tableau_linkedin.PNG'><br>
Check the interactive dashboard in <a href='https://public.tableau.com/profile/johan.klemantan.widagdo#!/vizhome/LinkedInJobVacancyAboutDatainIndonesia/Dashboard1?publish=yes'>My Tableau Profile here</a>
