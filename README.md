
BLUF: This repo showcases the work for Natural Language Processing as ARI525 progresses, and will continue to grow over time. It will grow from the top down as ne projects/sub-projects are added.

HW1: HW1_Reuters_Corpus_Processing
This proect leverages part of the work in HW0 (below) to apply tokenization to a downloaded corpus (Reuters-21578 was used), tokenize it, form a Bag of Words (BoW) representation of the individual documents and as a corpus, extract a vocabulary, and run simple categorization via a Naive-Bayes probability calculation and an implementation of Latent Dirichlet Allocation (LDA).

Requirements: Jupyter Notebooks, nltk, scikit-learn and gensim. This can only be run from a notebook in a virtual environment.


HW0: Tokenize_it
'tokenize_it' is a project that applies simple natural 
language processing(NLP)  techniques to an input file.

Requirements: A python virtual environment with pandas and nltk 
installed. The file should be executable (e.g. in Linux, 
chmod +x tokenize_it). Not entirely sure what Windows would do
with this file.

Usage: 

./tokenize_it --file path_and_filename [--lower] [--stop] [--stem] [--no-rares n]

Switches:

  --file takes a path and filesname. Required

  --lower lowercases the inout text. Not required.

  --stop removes stopwords based on the nltk stopwords corpus. Not required.

  --no-rares <n> removes words that appear n or less times in the input file. Not required.

Files in this folder:

  README.md this file

  HW1_Reuters_Corpus_Processing.ipynb, a notebook to perform NLP processing on the Reuters-21578 corpus

  Untitled.ipynb the scratch notebook used to get the syntax right

  alice.txt "Alice in Wonderland" from Project Gutenberg, as a sample input

  tokenize_it an executable (in Linux) python script

