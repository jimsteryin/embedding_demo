Cosine Similarity
- Measures angle between vectors
- Range: -1 to 1 (we exponentiate to get positive values)
- Doesn't depend on magnitude, only direction

Word Embeddings (GloVe)
- Each word → fixed-length vector
- Similar words → similar vectors
- Averaging loses word order!

Sentence Embeddings (Transformers)
- Whole sentence → single vector
- Captures context and word order
- Better for semantic similarity
 
OpenAI Embeddings
- State-of-the-art quality
- Large models = better performance
- Costs money (but has free tier)

Context: In this part, you are going to play around with some commonly used pretrained text embeddings for text search. For example, GloVe is an unsupervised learning algorithm for obtaining vector representations for words. Pretrained on 
2 billion tweets with vocabulary size of 1.2 million. Download from [Stanford NLP](http://nlp.stanford.edu/data/glove.twitter.27B.zip). 
Jeffrey Pennington, Richard Socher, and Christopher D. Manning. 2014. *GloVe: Global Vectors for Word Representation*.
