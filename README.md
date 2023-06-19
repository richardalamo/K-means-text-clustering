# K-means text clustering

In my project titled "Text Clustering", which can be found on [my website](https://www.ricardoalamosalgado.com/clustering), I utilized K-Means text clustering on the "Twenty News Group" dataset. The goal of this project was to group similar textual data into clusters, a technique that falls under the umbrella of unsupervised machine learning. The applications of this method are extensive, ranging from news aggregation and social media analysis to customer feedback analysis, email filtering, and search engine optimization. The project involved loading 100 articles, cleaning the book corpus, tokenizing and lemmatizing the text, and finally, vectorizing the preprocessed documents into a TF-IDF matrix. This TF-IDF matrix was then converted into a pandas DataFrame for further analysis.

I further detailed the steps involved in the process in the article. Tokenization is the process of breaking down text into individual words or terms, while lemmatization is the process of reducing words to their base or dictionary form. The TfidfVectorizer class from the scikit-learn library in Python was used to convert the collection of raw documents to a matrix of TF-IDF features. I then applied KMeans clustering to the high-dimensional data resulting from the TF-IDF vectorizer. The model had to find a balance between explaining the total variance and maintaining a reasonable number of clusters. After careful consideration, I determined that the optimal number of clusters was 10, which explained 14% of the variance and was a reasonable number considering the dataset contained 100 news articles.

In conclusion, my article emphasizes that K-means clustering requires a balance between maximizing the total variance explained and maintaining a reasonable number of clusters. While K-means is a popular choice, other machine learning algorithms might perform better for clustering text data. I suggest hierarchical clustering as an alternative and also mention the possibility of using other vectorization techniques such as Word Embeddings. The notebook for this project can be found on [GitHub](https://github.com/richardalamo/K-means-text-clustering/blob/main/Ricardo%20Alamo%20_F_Clustering%20Project.ipynb).

Data obtained from the popular dataset, "Twenty News Group," obtained from [https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html](https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html).




