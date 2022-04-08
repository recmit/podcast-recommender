# Podcasts Recommender

We train a podcast recommender using matrix-based collaborative filtering. Specifically, we use the [implicit](https://github.com/benfred/implicit) recommender library. Visualizing the resulting latent factors gives us some insight into what the model has learned (how the recommender "organizes" the podcasts, in a way).

[This](https://david-recio.com/2022/03/19/podcasts-recommender.html) blog post is a more reader-friendly version of the Jupyter notebook in which we train and evaluate the recommender.

The reviews data set used to train and evaluate the recommender is taken from [Kaggle](https://www.kaggle.com/datasets/thoughtvector/podcastreviews) (version 19).
