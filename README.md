# Bag Of Words

## Summary
Implementing a visual similarity search system based on the Bag-of-Features approach using Lucene.

##Objectives
- Developing an efficient similarity search system
- Evaluating effectiveness of the proposed approaches mAP

##Dataset
INRIAHolidays:
- Dataset size: 1491 images
- Ground-truth link with 500 queries and list of expected results
https://lear.inrialpes.fr/~jegou/data.php

##Expected Results
- Local features extraction
- Creation of dictionaries (about 100,000 should be fine but 10,000 is ok too) using k-means
- Online system able to perform similarity search
- Performing RANSAC to reorder the results

##Suggested Tools
- OpenCV
- Lucene
- Local Features: SIFT, SURF
