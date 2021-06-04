# Amazon-Fine-Food-Reviews
**Objective:**
Classification of user reviews on Amazon Food products into two categories (Positive or Negative) & deployment of the model using Heroku.
Given a review, determine whether the review is positive (Rating of 4 or 5) or negative (rating of 1 or 2)

**Data Source:**
https://www.kaggle.com/snap/amazon-fine-food-reviews

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.

     Number of reviews: 568,454  
     Number of users: 256,059
     Number of products: 74,258
     Timespan: Oct 1999 - Oct 2012
     Number of Attributes/Columns in data: 10 

**Files:-**
* The entire source code of the final trained model is in model.py file & is stored in model.pickle format
* The app.py consists of source code for deployment of model using Flask API.
* Files necessary to deploy model on Heroku (requirements.txt, Procfile and runtime) are also available. 

**How to Use:-**
* The model is deployed at https://sentiment-analysis-abd.herokuapp.com/index .
* Just enter the review text in review Text box & PRESS Submit button to predict wheather the input review is 'POSITIVE' Or 'NEGATIVE'.

**Note :**
    Here we are purposefully ignoring reviews with score equals to 3 as there are Neutral , and if the score is above 3 then the  review will be set to "Positive" , otherwise it will be set to "Negative".
