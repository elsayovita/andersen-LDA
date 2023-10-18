# Understanding Hans Christian Andersen's short stories using LDA
This project used LDA to discover common topics discussed in Hans Christian Andersen's short stories.
Stories were retrieved from the Project Gutenberg website (https://www.gutenberg.org/files/27200/27200-h/27200-h.htm#year) using Python, mainly BeautifulSoup.
The retrieved text was preprocessed using nltk into word tokens - which involved tokenization, case-lowering, stopword/ punctuation removal, pos tagging, and lemmatization.
Post-processing, LDA model was used to fit tokens into topics.
Based on the coherence score and interpretability, 5 topics were chosen, namely 'winter folklore', 'moral virtues', 'food-related', 'nature', and 'people and society'
