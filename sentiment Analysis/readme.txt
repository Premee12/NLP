There are two sentiment analysis initiatives inside this project. In the first portion, a dataset without any labels was subjected to Textblob sentiment analysis to identify tweets that were positive, negative, or neutral.

The phrases in the second section are taken from positive or negative reviews of goods, movies, and restaurants.

=======
Format:
=======
sentence \t score \n

The score ranges from 0 (negative) to 1 (positive).

The phrases come from three different sources: yelp.com, amazon.com, and imdb.com.

There are 500 positive and 500 negative sentences for each website, chosen at random from bigger databases of reviews. In order to avoid selecting any neutral sentences, only sentences that had a clear positive or negative connotation were chosen. 
These sentences were then concatenated to form one dataset.


For each website, there exist 500 positive and 500 negative sentences. Those were selected randomly for larger datasets of reviews. 
We attempted to select sentences that have a clearly positive or negative connotaton, the goal was for no neutral sentences to be selected.



For the full datasets look:

imdb: Maas et. al., 2011 'Learning word vectors for sentiment analysis'
amazon: McAuley et. al., 2013 'Hidden factors and hidden topics: Understanding rating dimensions with review text'
yelp: Yelp dataset challenge http://www.yelp.com/dataset_challenge
