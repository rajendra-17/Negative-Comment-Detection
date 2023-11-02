# Toxic-Comment-Classification

<h3> Brief Introduction</h3>

An NLP model that can predict the probability for each type of toxicity of comments.

<h3> Overview </h3>

Engaging in meaningful discussions can be challenging, especially online, where the threat of abuse and harassment often stifles open expression and diverse viewpoints. Many platforms struggle to effectively manage conversations, leading some communities to restrict or entirely disable user comments. The Conversation AI team, a research initiative jointly founded by Jigsaw and Google (both part of Alphabet), is dedicated to improving online discourse. Their primary focus lies in understanding and addressing negative online behaviors, such as toxic comments characterized by rudeness, disrespect, or behavior likely to discourage participation.

You are provided with a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. The types of toxicity are:

- toxic
- severe_toxic
- obscene
- threat
- insult
- identity_hate

You must create a model which predicts a probability of each type of toxicity for each comment.

<h3>File descriptions</h3>

* <b>train.csv</b> - the training set, contains comments with their binary labels
* <b>test.csv</b> - the test set, you must predict the toxicity probabilities for these comments. To deter hand labeling, the test set contains some comments which are not included in scoring.
* <b>sample_submission.csv</b> - a sample submission file in the correct format
* <b>test_labels.csv</b> - labels for the test data; value of -1 indicates it was not used for scoring;

<h3>Usage</h3>

The dataset under CC0, with the underlying comment text being governed by Wikipedia's CC-SA-3.0

For more details : https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/overview
