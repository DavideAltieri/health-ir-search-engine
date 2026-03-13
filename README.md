# Health IR Search Engine

This project explores the development of an Information Retrieval system designed to retrieve relevant medical documents from user health-related queries. The system is built and evaluated using the **NFCorpus dataset**, which contains thousands of medical abstracts and user queries annotated with relevance judgments.

The goal of the project is to analyze how different retrieval techniques influence the precision of search results. After an initial analysis of the dataset, we implemented a basic search engine pipeline including text preprocessing, indexing, retrieval, and evaluation.

During preprocessing, queries and documents were cleaned through tokenization, stopword removal, and stemming to ensure consistency between the indexed content and user queries. We then experimented with classical Information Retrieval models such as TF-IDF and BM25, testing different indexing strategies based on document text, titles, and their combination.

To further improve the retrieval effectiveness, we explored several advanced techniques. These include query expansion, which generates semantically related query variations, a sliding window indexing strategy to better handle long documents, and a BERT-based re-ranking approach aimed at refining the ranking of retrieved documents through deeper semantic understanding.

The system is evaluated using standard Information Retrieval metrics such as Mean Average Precision (MAP) and Precision at rank 5 and 10 (P@5, P@10). Through a series of experiments, the project investigates how traditional retrieval models and more recent neural approaches impact the quality of search results.
