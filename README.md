# GoodReads Recommendation system

## To-Do List

### **Data**
- [x] `Goodreads dataset`: Write web scraping code to create Goodreads dataset. **Albert**
- [x] Clean and preprocess data **Mark**
- [x] Process genres (from string to lists) **Albert**
- [x] Create train-test split for evaluation **Mark**

### **Frequent itemset algorithms**
- [x] `Apriori`: Implement `Apriori` algorithm from scratch and assert that it gives the same output as `mlxtend.frequent_patters.apriori` **Albert**
- [ ] `PCY`: Implement `PCY` algorithm from scratch and assert that it gives the same output as another python package. **Frederik**
- [x] Compare the two algorithms based on time taken, memory used, and number of patterns found. **Albert**

### **Clustering**
- [x] `K-means`: Implement `K-means` clustering. **Mark**
- [ ] `DBSCAN`: Implement `DBSCAN` clustering. **Bendix**
- [ ] Calculate Davies-Bouldin index for both clustering types. **Mark**
- [x] Visualize clusters for K-Means. **Mark**
- [ ] Visualize clusters for DBSCAN. **Bendix**

### **Recommendation system integration**
- [x] Using frequent itemsets (Apriori/PCY)
- [ ] Using clusters (K-means/DBSCAN)
- [ ] Combine both approaches

### **Evaluation**
- [ ] `Metrics`: Implement metrics to quantify the performance of Goodreads recommendation system using `Aprior`, `PCY`, `K-means` and `DBSCAN`.
    - [ ] Genre matching score (the system recommends books with similar genres)
    - [ ] Rating prediction accuracy (the system recommends books with similar ratings)
    - [ ] Recommendation diversity (the system gives diverse recommendations)
     
        
- [ ] `Topic not taught in class`: Implement a topic / metric / algorithm not taught in class.
