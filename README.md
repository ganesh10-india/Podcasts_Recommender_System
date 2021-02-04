# Podcasts_Recommender_System
In this project, I use a word embedding neural network and do some NLP on podcast transcriptions from "This American Life" in order to ultimately create a recommendation Flask app.

**Objective: "How can we get more people to get into podcast listening?"**
The goal of this NLP project is to attempt to use data science techniques to make it easier on users to start listening to podcasts, and use machine learning to generate personalized recommendations so that they can continue once they've started. The transcripts of each podcast will be carefully scraped from thisamericanlife.org, explored and visualized via Jupyter Notebook, modeled via a flask app.

**Note: The following files are not available because they are too large for GitHub "uncleaned_podcasts.csv" and "w2v.pkl"**

## Scraping and Cleaning the Podcast Transcriptions
- Scrape the podcast transcriptions from "This American Life"
- Clean the data and prepreocess the transcriptions for ease of use later on

## Providing a Starting Point & Generating Recommendations

- Upload Google's pretrained word embedding neural network to vectorize all the podcasts
- Develop techniques to put podcast vecotors, user vectors, and search query vectors in the same word embedding space
- Use cosine similarity to generate recommendations and search results
- Topic Model on the corups using TF-IDF and NMF
- Create a word cloud for presentation

## Flask App Search & Recommender, and Presentation

- Create an app using Flask that will allow the user to search, and store a user's likes to then make recommendations based on all their likes. 

