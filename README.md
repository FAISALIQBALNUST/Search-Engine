# Search-engine-implementation

SearchWright - A Python-Based Search Engine

Overview:
SearchWright is a powerful search engine designed to efficiently search and retrieve relevant documents from a dataset of 190K+ articles using TF-IDF ranking. The system handles multi-word queries, removes stop words, and ranks results for improved accuracy.

Key Features:

Efficient search algorithm using TF-IDF for precise document ranking.
Implements Lexicon, Inverted Index, and Forward Index data structures for fast lookups.
Handles large datasets with optimized data processing techniques.
Provides a user-friendly interface for querying and browsing results.
Technologies Used: Python, Pandas, NLTK, CSV Processing

Usage:

Clone the repository.
Run divide.py to extract 50K rows from the dataset.
Clean the data using clean.py.
Build data structures with lexicon.py, forwardIndex.py, and invertedIndex.py.
Use query.py to input search queries and receive ranked results.
