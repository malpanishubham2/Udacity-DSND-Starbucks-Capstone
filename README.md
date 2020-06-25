# Udacity Data Science Nanodegree Starbucks Capstone Project
## Installation
- Python versions 3.*.
- Libraries used:
    - Pandas
    - Numpy
    - Matplotlib
    - Seaborn
    - Scikit learn
 ## Motivation
Once every few days, Starbucks sends out an offer to users of the Starbucks rewards mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or a buy one get one free.

I wanted to analyse what happens with that offer which starbucks sends out. Is it just viewed? Is it used and a transaction has been performed?
So in this project we are going to answer these questions and make a model which is best for this scenario.
## Files Description
1. The file `Starbucks_Capstone_notebook.ipynb` is written in a Jupyter Notebook, and follows the `CRISP-DM` process.
- First we state the questions that we need to answer.
- Next we get a jist of the data.
- Then we pre process the data for visualization 
- Then we perform some data visualization to get some more insights.
- After that we make a dataframe just for modelling purpose and run various machine learning algorithms on it.
- Finally we summarize our findings.
2. Datasets
- portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.).
- profile.json - demographic data for each customer.
- transcript.json - records for transactions, offers received, offers viewed, and offers completed.(Wasnt able to upload this one as above 25 mb)
## Results
- Income of everyone is between 30k and 120k where men earn more in the lower spectrum (less than 75k) and women earn more in the higher spectrum.
- There are 17k customers in the database with almost 2175 with no age,gender or income. These are the people who dont want to give their personal details.
- The most common offer type among all age groups is the BOGO , followed by the Discount Offers. Whereas, the least common offer to be sent is the informational offers. I believe that BOGO offers are more attractive compared to other offers provided by Starbucks.
- Finally i would conclude that i have successfully made a model which tells with 87% accuracy that what happens when a customer is presented with an offer. I really enjoyed doing the whole project. Though it was very extensive it was fun and engaging.
## Blogpost
Here is the [link](https://medium.com/@shubham.malpani/analyzing-starbucks-data-c3d7b137f4b3) to the blogpost.
