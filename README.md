# Extract data
First, I extracted data from ferdowsi-data.txt, which Its size was 14GB. Because of its large size, it had to be read line by line. After extracting data and make data frame, I save results in Data.csv.

# Preprocess on news dataset
In this project, first I start to visualize data in 3 groups to understand better data set, which locate on data_visualization. Second I use hazm library for text processing in Persian data set on DataCleaning file.

# clustering on news dataset

In this session, I use 1000 text of news for clustering in three ways:

•	kmeans + BOW(bag of words)

•	kmeans + tf-idf

•	kmeans + fasttext


kmeans + BOW and kmeans + tf-idf are located on Clustering
kmeans+ fasttext are located on Clustering_fasttext 

