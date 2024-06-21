 The user can enter a question, and the code retrieves the most similar questions from the dataset using the util.semantic_search method.

- This is a symmetric search task, as the search queries have the same length and content as the questions in the corpus.

- Quora Questions Dataset: https://www.quora.com/q/quoradata/First-Quora-Dataset-Release-Question-Pairs



- As embeddings model, we use the SBERT model `quora-distilbert-multilingual`,
that it aligned for 100 languages. I.e., you can type in a question in various languages and it will return the closest questions in the corpus (questions in the corpus are mainly in English).
