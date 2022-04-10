Constructed Random forest algorithm to predict the final autism-risk association gene scores various statistics

Statistics used to train models:
1. BrainSpan scores from BrainSpan_score random forest model
2. String scores from String_score random forest model
3. TADA statistics
4. DAWN scores
5. DAMAGES scores
6. Krishnan et al scores

Generate supp table 2 that contains gene-risk prediction scores from each fold of cross validation (CV) and the average over five folds.

**Data Preprocessing**

Preprocess data to train the models
1. Build network graph from STRING Data
2. Build gene wise expression matrix from BrainSpan data
3. Handle missing data
4. Generate training data

**BrainSpan-score model**

1. Train BrainSpan-score model in layer 1 to predict BrainSpan scores
2. Generate supplement table 1 that shows involvement of genes in autism