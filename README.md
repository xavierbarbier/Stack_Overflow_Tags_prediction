# Stack Owerflow tags prediction

**Context :**

Stack Overflow is the largest, most trusted online community for developers to learn, share​ ​their programming ​knowledge, and build their careers.

Created in 2008 by Jeff Atwood and Joel Spolsky, Stack Overflow has over 10 million registered users by January 2019 and it exceeded 16 million questions in mid 2018.

The website serves as a platform for users to ask and answer questions, and, through membership and active participation, to vote questions and answers up or down and edit questions and answers in a fashion similar to a wiki or Reddit.

The website also relying on tags associated with users questions. Tags helps to more easily receive response from the community. But it represent a challenge to new users who does not always which tags to use.

The goal of this project is to work on supervised and unsupervised learning that predict tags to use, base on title and body texts.

## Data
Data are collected from stackexchange explorer : https://data.stackexchange.com/stackoverflow/query/new.

## Cleaning
* html code removal
* suppress ponctuation and stopwords
* Tokenisation
* Lemmatisation

Cleaning notebook => https://github.com/xavierbarbier/Stack_Overflow_Tags_prediction/blob/main/stack_overflow_01_cleaning.ipynb

## Exploration
* Central tendencies
* Term frequency for tags, title and body

Exploration notebook => https://github.com/xavierbarbier/Stack_Overflow_Tags_prediction/blob/main/stack_overflow_02_exploration.ipynb

## Modeling
### Supervised
* features engineering
* words representation (bag of words, tf-idf)
* multi-label classification
* scoring with Jaccard Score

### Unsupervised 
* features engineering
* Latent Dirichlet Allocation
* Topics optimisation with log likelyhood

Modeling notebook => https://github.com/xavierbarbier/Stack_Overflow_Tags_prediction/blob/main/stack_overflow_03_modelisation.ipynb

## API
App was deploy on Heroku using Dash library.

API => https://stack-overflow-auto-tag.herokuapp.com/

## Presentation slides

Slides => https://github.com/xavierbarbier/Stack_Overflow_Tags_prediction/blob/main/stack_overflow_presentation.pdf

## Memo

Document => https://github.com/xavierbarbier/Stack_Overflow_Tags_prediction/blob/main/stack_overflow_rapport.pdf


