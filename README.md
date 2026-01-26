BLUF: 'tokenize_it' is a project that applies simple natural 
language processing(NLP)  techniques to an input file.

Requirements: A python virtual environment with pandas and nltk 
installed. The file should be executable (e.g. in Linux, 
chmod +x tokenize_it). Not entirely sure what Windows would do
with this file.

Usage: 
./tokenize_it --file <path and filename> [--lower] [--stop] [--stem] [--no-rares <n>]

Switches:

  --file takes a path and filesname. Required

  --lower lowercases the inout text. Not required.

  --stop removes stopwords based on the nltk stopwords corpus. Not required.

  --no-rares <n> removes words that appear n or less times in the input file. Not required.


Files in this folder:
  README.md this file

  Untitled.ipynb the scratch notebook used to get the syntax right

  alice.txt "Alice in Wonderland" from Project Gutenberg, as a sample input

  tokenize_it an executable (in Linux) python script
