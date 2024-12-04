# GoodReads Recommendation system

## To-Do List

### **Data**
- [x] `Goodreads dataset`: Write web scraping code to create Goodreads dataset. **Albert**
- [x] Clean and preprocess data **Mark**
- [x] Process genres (from string to lists) **Albert**
- [x] Create train-test split for evaluation **Mark**

### **Frequent itemset algorithms**
- [x] `Apriori`: Implement `Apriori` algorithm from scratch and assert that it gives the same output as `mlxtend.frequent_patters.apriori` **Albert**
- [x] `PCY`: Implement `PCY` algorithm from scratch and assert that it gives the same output as another python package. **Frederik**
- [x] Compare the two algorithms based on time taken, memory used, and number of patterns found. **Albert**

### **Clustering**
- [x] `K-means`: Implement `K-means` clustering. **Mark**
- [x] Calculate Davies-Bouldin index for clustering. **Mark**
- [x] Visualize clusters for K-Means. **Mark**

### **Word2Vec**
- [x] Implement word2vec (topic not taught in class).**Bendix**
- [x] Visualize word2vec via neighbor graph and louvain cluster. **Bendix**

### **Recommendation system integration**
- [x] Using frequent itemsets (Apriori/PCY) **Albert**
- [x] Using clusters (K-means) **Albert**
- [x] Using word2vec

### **Evaluation**
- [ ] `Metrics`: Implement metrics to quantify the performance of Goodreads recommendation system using `Aprior`, `PCY`, `K-means` and `word2vec`.
    - [X] Similarity metrics for word2vec embeddings
    - [X] Genre matching score (the system recommends books with similar genres) **Frederik**
    - [X] Rating prediction accuracy (the system recommends books with similar ratings) **Frederik**
    - [ ] Recommendation diversity (the system gives diverse recommendations)
