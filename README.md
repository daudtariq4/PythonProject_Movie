
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









