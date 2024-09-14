
# SUDACINEMA

Content Based Movie Recommender System

## Workflow

### Step 1
> Download Data set from kaggle ([LINK](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata))

### Step 2
> Create a jupyter notebook for model building

### Step 3
> Import libraries
  ```python
  import numpy as np # linear algebra
  import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)
  ```
### Step 4 
> Create dataframes 'movies' and 'credits' and merge them
![Screenshot (2739)](https://github.com/user-attachments/assets/751449b5-feb1-4059-a1a9-d1b2c504998f)

### Step 5
> Remove non-relevant columns,  missing and duplicate data
![Screenshot (2740)](https://github.com/user-attachments/assets/edeef0bc-5382-4abf-94ec-fd55a691f6cf)

### Step 6
> To create a column 'Tags' by merging 5 columns, we preprocess and clean the data in those columns
![Screenshot (2741)](https://github.com/user-attachments/assets/ed1d23dc-ad77-4fee-8c77-10c8d0aee30d)

### Step 7
> The strings are concatenated and we get clean data
![Screenshot (2742)](https://github.com/user-attachments/assets/ee37296e-3759-4598-b5dc-afbfe3f34a7b)

### Step 8 
> Perform vectorization by importing CountVectorizer library from sklearn class
![Screenshot (2743)](https://github.com/user-attachments/assets/aa920134-d60a-4609-bf3a-d90b33725696)

### Step 9 
> Import cosine_similarity function from sklearn library and find similarity among vectors
![Screenshot (2744)](https://github.com/user-attachments/assets/f63a974d-2da0-49dc-8e3a-550211731ea1)

### Step 10
> Sort movies on the basis of similarity, this will be used in main function
  ```python
sorted(list(enumerate(similarity[0])),reverse=True, key=lambda x:x[1])[1:6] 
  ```
### Step 11
> Create main function, which will return 5 similar movies
![Screenshot (2745)](https://github.com/user-attachments/assets/ece27ca5-1f28-425f-b5d8-abff8e448cd2)

### Step 12












