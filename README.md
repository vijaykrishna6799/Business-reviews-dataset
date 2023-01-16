# Business-reviews-dataset
## Datasets downloades from https://www.yelp.com/dataset (It is exceeding 100MB for me to upload in github)
extract the Yelp Dataset and Merge Business and Reviews Dataset for analysis
For detailed implementation goto main_doc.pdf

This project is mostly about businesses with at least R reviews in two different metropolitan areas. Use the following approach:
a. Identify the total number of reviews for each business in one metropolitan area.
b. Keep only those businesses with at least R reviews and remove all others.
c. Among the remaining businesses, when two businesses have been reviewed by the same reviewer, connect them.
d. Draw this graph and compute the degree centrality of all vertices. Compute the average
degree centrality of all nodes.
e. Repeat for a second metropolitan area and compute the new average degree centrality of all nodes in the new metropolitan area.
f. Do you see any difference in these two values? Explain.
