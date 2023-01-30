# 
In order to build this RS -
    1. Downlaod the dataset from these link https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
      there are two datasets available i.e. credit and movies
    2. Merge both the datsets 
    3. Perform preprocessing on the resultant dataset and then transform them to same type of data , I converted into list of strings
      3.1 Remove null and duplicate values 
    4. At the end we get three attributes that are movie id , title , and the tag 
    5. Computing the cosine similarity 
We can choose any movie from the list of thousand movies . The code will suugest the similar top 5  movies or any number we can give.
