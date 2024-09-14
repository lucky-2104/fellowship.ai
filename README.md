# fellowship.ai


Analysis
We can see from this notebooks data that TF-IDF approach for all the ML algorithms has performed well in terms of accuracy in comparison to with BOW(bag of words). This can attribute to :

Handling common words : In sentiment analysis , certain words might frequently occur accross some classes , making it challenging for BOW to differentiate sentiments meaning and context . TF-IDF balances the significance of words, reducing bias towards frequent , but less informative words.

Term Weighting : TF-IDF assign higher weights to terms that are frequent in document but rare across the corpus , emphasizing their importance in discriminating between classes.

Semantic Understanding : TF-IDF gives semantic relevance to terms , allowing model to give more weights to words having more relevance with respect to the context.

Dimentionality Reduction : TF-IDF reduces the impact of frequently occuring words(stop words) by assigning lower weights to them. Dimentionality reduction also helps in focusing on the essential discriminating features.

Normalization : TF-IDF nomalizes the importance of words across documents, making the represention more robust and reducing the impact of document length on the analysis

Reducing Noise : TF-IDF can reduce the noise in the data by diminishing the influence of common words and increasing the impact of more rare words used in the reviews potentially imporving the models ability to generalize the unseen data.

While training the deep learning model we encounted with the problem of overfitting which was later encountered by L2 regularization and early stopping.

Both Stochastic Gradient descent and Logistic regression did extremely well in classification task providing accuracy of ~ 87%

Word2vec didnt prove effective.
