# Sentiment-Analysis

This set is a collection of movie review documents labeled with respect to their overall sentiment polarity (positive or negative). The set was released  by stanford.edu and it contains 25000 test and 25000 train processed dataset. The reviews were preprocessed by the dataset editors so that each review iS formatted as a plain tokenized text, containing no structured information that can imply on the polarity of the text (e.g. stars rating – 0/5). The average review size  (in words) is 746.3.

This dataset is taken from https://ai.stanford.edu/~amaas/data/sentiment/ and then preprocess to put all positive and negative reviews in the same file for training and testing. It helps in put more effort on algorithm instead of data collection.

Content
The slides are at https://colab.research.google.com/drive/1vPcfre7S05eJ2xVtawNmAPozxfXNIY27#scrollTo=75yt5uAR-eN0

The interactive notebooks are in the main folder.

Classification Accuracy
Scores ~87% accuracy on positive response.
https://github.com/todcru/Sentiment-Analysis/blob/main/sentimentanlysis.ipynb
Scores ~88% accuracy on negative response.
https://github.com/todcru/Sentiment-Analysis/blob/main/sentimentanlysis.ipynb

Features are extracted and learned using Python and Jupiter, and evaluated by building a logistic regression classifier on a weighted tf-idf feature vector.
Viewing the notebooks online
The content of the notebooks can be viewed online through colab.research.google.com/

Installing Python

For a true interactive use of the notebooks you need to install Python, IPython (for notebooks) and the required libraries scikit-learn, matplotlib and numpy.

Windows
You can install everything at once using a complete scientific Python distribution. Two good ones are the Enthought Python distribution (EPD, free for academic use) or Python-(x, y) (free for everyone).

Mac
For OS X, you can also use the Enthought Python distribution or the scipy-superpack.

Linux
Just use your package manager, for example on ubuntu or debian, use apt-get install python ipython python-matplotlib python-numpy python-sklearn.

Version requirements
You need to make sure to have at least IPython >= 0.11 installed. You can update using the programm easy_install.

Installing Scikit-learn
More tips on installing scikit-learn can be found on the scikit-learn website.
