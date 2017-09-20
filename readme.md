## Sentence Selection for Python (Sept, 2017) ##


----------
Code for the paper PAPER_TITLE

Requirement
-------

 - Source code is written in Python 3.5 (Anaconda Environment), and requires Keras (TensorFlow [GPU] back-end)
 - Use the pre-trained [*word2vec*](https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?usp=sharing), published by Mikolov *et al.*

Run the model
-------

 - Download all pre-processed datasets in `data` directory
 - Run this command for evaluating Feed-forward neural network model: `python ann.py`
 - Run this command for evaluating Convolutional neural network model: `python conv1d.py`
 - All above programs perform three phases: (1) build the model, (2) compute `accuracy` on training and testing datasets, and (3) save model to disk