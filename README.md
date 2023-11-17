# DiFaR based recommender system
This is a implementation of a recommender system which is based on ["Direct Fact Retrieval from Knowledge Graphs without Entity Linking"](https://arxiv.org/pdf/2305.12416.pdf).  

This is an ongoing research.  

# Required dataset:
- MovieLens 100k dataset
- Yahoo!Movies dataset (Authorization from [Yahoo! Reasearch team](https://webscope.sandbox.yahoo.com/catalog.php?datatype=r) is needed)

# Constructing KG
```
run the construct_kg.ipynb
```

# Constructing KG triplet sequence
```
run the dataset.ipynb
```  
```Triplet (movie_title - relation - attribute) sequence for LM:```  
```
[CLS] head [SEP] relation_1 tail_1 relation_2 tail_2 ... relation_k tail_k [SEP]
```

# The retrieval model:
```
run the retrieval.ipynb
```  