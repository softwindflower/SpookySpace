# HackUTA
## Inspiration

To make Halloween a better experience for others, we sum up all the fun activities in the palm of your hand. The website we made has updates on nearby Halloween events, games and many other fun activities. 


## What it does

Some of the features of our website includes basic machine learning models that would rate Halloween costumes  and check for allergens in common Halloween candies. On our website, a user could submit a photo of their costume and our model would rate it based on what it was trained on. For the candy model, you would send a picture of the candy you have and it would list the allergens it may possibly contain. 

## How we built it

Our project has three components; front end, back end, and the cloud server.  For front end we used HTML and CSS to create a website that would host our ML models. For our back end we built a machine learning model using train_test_split on a Halloween candy bar analysis dataset. We then used Logistic Regression to use that model into predicting if it is a chocolate bar or not. For the cloud server, we used a flask web application and deployed it onto Google Cloud, alongside both our front end and back end elements.

## Challenges we ran into

While building the website, we could not figure not how to add the file path to the pictures we selected into the HTML code. Also, we had a hard time figuring out which ML model would be the best option to use predicting the target variable. We ran into trouble when we were finding patterns and could not figure how can we best portray our data visualization to find pattern. Converting string into int/float took a lot of our time while trying to visualize the data. Working with Google Cloud also took up plenty of our time, with lots of debugging that needed to be done.



## Accomplishments that we're proud of

It was our first time working as a team, and we were able to finish our website and successfully train our ML models and integrate it onto Google Cloud.  Coming into the hackathon, we were not the most experienced in any of the things that we did, but we were able to teach ourselves on the fly and actually finish our project. In the end, we came out with a lot more experience and confidence in the skills that we learned.

## What we learned

We got to learn about building a website, finding current paths for different types of files in HTML, integrating ideas through github repository and collaborate with each other. Alongside, we got to learn about libraries (i.e. NumPy, Scikit-Learn, Pandas) in Machine Learning Algorithms and how we can implement those libraries to predict real world problems. We also sharpened our python skills while working on the back end portion and also the cloud portion. 


## What's next for Spooky Space

Polishing the website and adding more ML Models, and potentially a chatbot. 

## Dataset Used
https://www.kaggle.com/datasets/fivethirtyeight/the-ultimate-halloween-candy-power-ranking/data


