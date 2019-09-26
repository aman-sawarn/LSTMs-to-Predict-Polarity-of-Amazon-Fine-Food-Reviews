# LSTMs-to-Predict-Polarity-of-Amazon-Fine-Food-Reviews

  Check code file for documentation
  
  
The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.
In this we will remove duplicate values and missing values and we will focus on ‘text’ and ‘score’ columns because these two columns help us to predict the reviews.
The Score column is ranged from 1 to 5, and we will remove all Scores that are equal to 3 because we assume these are neutral and did not provide us any useful information. We will add a new column called “Positivity”, where score above 3 is represented as a 1,we say it was positively rated. Otherwise, it’ll be represented as a 0, indicating it was negatively rated.
