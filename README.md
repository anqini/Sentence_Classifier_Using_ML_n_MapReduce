# Yelp Classifier
Author: Anqi Ni

## Intro
This is a project for yelp comments classification. The basic machine leanring algorithm we use is the naive bayers classification. Since we are dealing with sentence, we user a basic language model: **bag of word** (pretty outdated though). Since we have thousands of sentence to deal with, and each sentence has its own lenghth, the total time to compute is unpredictable. Thus, **Map Reduce** comes to our mind. We use Hadoop Spark mapreduce to make the computation more efficient.

## Key words
- Machine learning
- Naive Bayers
- Map Reduce
- Hadoop
