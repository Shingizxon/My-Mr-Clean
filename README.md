# Welcome to My Mr Clean
***

## Task
It is time to get our hands dirty and to manipulate some real world data. You have been hired by a new company named EncyclEarthpedia and your first task it build a search engine.
EncyclEarthpedia is an online encyclopedia but specialized in the planet Earth, its geology, biology, and everything related to the Earth.

The search engine should be simple at first. The user needs to be able to type some words and the engine returns the most relevant articles.

There is a problem though. The engineers working on the database messed up and EncyclEarthpedia's database and API are not available for a week.
This is a bummer ! If we can't have access to the articles, how are we going to build our engine ?

Instead of waiting for a week, we are going to build a simple model for some similar article from Wikipedia.

What we are going to do is:

Get some article from Wikipedia to work with.
Extract meaningful and usable content from this article.
Clean up and filter the data to narrow the scope to relevant words
Build a simple frequency model.
Analysing the article based on this model.
This first work of this article would be the start of our search engine, using some notion from Information Retrieval and tf-idf statistic.

## Description
We have solved it with functions. Create a function get_content(article_name) to retrieve information about an article.

## Installation
Run it with jupyter... Then python file_name.py

## Usage
The most frequent words should be more relevant to match this Ozone layer article content. If the user's search is made of the words "Ozone" and "gas", we can vectorize articles and represent them with a vector of size 2. The coefficient of the vectorized article would be the frequencies of the words from the search. By vectorizing all articles this way, we can build some kind of distance between articles.
Another data engineering technique we could have had explored is stemming to get even more insight about the article.

### The Core Team
suxrobov_s Siroj Sukhrobov
sodiqov_o O'rolbek Sodiqov
<span><i>Made at <a href='https://qwasar.io'>Qwasar Silicon Valley</a></i></span>
<span><img alt='Qwasar Silicon Valley Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
