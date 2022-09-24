# Detecting-sentiments-in-tweets-using-NLP
## Background Information
According to the WHO, one in every 100 deaths is due to suicide [1]. Today, suicide is one of the main causes of death among young people in Europe.

In addition, social networks, which serve to express ideas, opinions or feelings, also influence this problem. Many young people who have problems use social networks to express their emotions and in some cases self-harming tendencies.
Furthermore, social problems such as the economic crisis or the current health crisis exacerbate this problem [2].

For this reason, some social networks such as Twitter are committed to developing algorithms to detect these trends and feelings, avoiding extreme cases by offering help.
In this regard, artificial intelligence can help since algorithms can be developed to predict these situations.

## Motivation and Objective
The motivation of the project consists in avoiding these tragic events and providing a useful and simple tool to health professionals and emergency services.

The objective of this work is to develop an algorithm capable of predicting emotions and feelings in social networks. In addition, it is intended to quantify these emotions and try to visualize possible patterns.

At its core, this project is a Dash application hosted in a local web server, capable of introducing an existing user on Twitter, obtaining their latest (100-200) tweets and classifying them by emotions. It also features functions to generate word clouds and extract the intensity of each emotion in the corpus of tweets extracted.

## TWITTER EMOTION ANALYZER
This is a Dash app which fetches and classifies tweets from a given username. It also generates cool visualizations from the processed data.

It was our final project for the 2nd Edition Samsung Innovation Campus AI Course with the University of Málaga (UMA).

## REQUIREMENTS AND VIRTUAL ENVIRONMENT

First off, make sure you are in the project folder.

Then execute this file in order to activate the virtual environment we created:

./project_venv/Scripts/activate

Once you have activated the venv (it should show in parentheses in your console), use the package manager pip to install the required packages from requirements.txt:

pip install -r requirements.txt

RUNNING THE APP

Once the virtual environment is active and requirements are installed, run the app.py file:

python app.py
