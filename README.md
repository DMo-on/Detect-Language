# Detect Language:
 I used a stopwords based approach.
 
* First step is to “tokenize”.
* NLTK gives us stopwords for several languages (here I used Arabic,French and English stopwords).
* I compute language probability depending on which stopwords are used.
* Finally, I chose the “key” with the biggest “value”.
