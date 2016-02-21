# Bag Of Words

## Summary
Implementing a visual similarity search system based on the Bag-of-Features approach using Lucene.

##Objectives
Developing an efficient similarity search system
Evaluating effectiveness of the proposed approaches mAP

##Dataset
INRIAHolidays:
  1) Dataset size: 1491 images
  2) Ground-truth link with 500 queries and list of expected results
https://lear.inrialpes.fr/~jegou/data.php

##Expected Results
  1) Local features extraction
  2) Creation of dictionaries (about 100,000 should be fine but 10,000 is ok too) using k-means
  3) Online system able to perform similarity search
  4) Performing RANSAC to reorder the results

##Suggested Tools
  1) OpenCV
  2) Lucene
  3) Local Features: SIFT, SURF
