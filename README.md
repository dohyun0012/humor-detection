# Humor Detection

Humor is something that feels very human. If I can hold a long conversation with a computer and laugh at its humor, then I would be convinced that we are living in an AI age.

The first step to creating a humorous AI agent would be to gather "funny" content and build a model that understands what's "funny".

The Yelp Dataset Challenge dataset contains more than two million Yelp reviews. Users can tag these reviews as "Useful", "Funny", or "Cool". I gathered reviews which had more than 10 "Funny" tags and built a model to learn the features that make up these reviews. I tried several models. Logistic Regression and Naive Bayes were the most successful. My implementation of a simple neural network model using TensorFlow did not work as well.

`data.ipynb` preprocesses the Yelp Dataset Challenge dataset
`model.ipynb` builds models using a machine learning pipeline
`model_nn.ipynb` implements the neural network model using TensorFlow

Citation:
https://cs224d.stanford.edu/reports/OliveiraLuke.pdf
