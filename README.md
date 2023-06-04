# GloVe

GloVe Word Embedding Implementation
This repository contains an implementation of the GloVe (Global Vectors for Word Representation) model for generating word embeddings. It processes a given corpus of text, constructs a co-occurrence matrix, and trains the GloVe model to generate embeddings.

Prerequisites
You will need the following Python libraries:

numpy
collections
itertools
math
tabulate
matplotlib

If you don't have these libraries, you can install them with pip:
pip install numpy tabulate matplotlib

How to Run the Script
Save the script in a file, let's say glove_implementation.py.
If you have a specific corpus of text you want to use, replace the corpus variable in the script with your data.
Run the script in your terminal:
python glove_implementation.py

Expected Outputs
The script will print the co-occurrence matrix, the learned embeddings for each word in the vocabulary, and tables comparing the performance of the reproduced and extended GloVe model. It will also generate bar graphs and pie charts of these results.

License
MIT
