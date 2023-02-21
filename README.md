# Business-reviews-dataset
## Datasets downloades from https://www.yelp.com/dataset (It is exceeding 100MB for me to upload in github)
extract the Yelp Dataset and Merge Business and Reviews Dataset for analysis
For detailed implementation goto main_doc.pdf

This project is mostly about businesses with at least R reviews in two different metropolitan areas. Used the following approach:
- a. Identified the total number of reviews for each business in one metropolitan area.
- b. Keep only those businesses with at least R reviews and remove all others.
- c. Among the remaining businesses, when two businesses have been reviewed by the same reviewer, connected them.
- d. Drawn a graph for that and computed the degree centrality of all vertices. Computed the average degree centrality of all nodes.
- e. Repeated for a second metropolitan area and computed the new average degree centrality of all nodes in the new metropolitan area.
- f. Difference in these two values are observed and explained.
