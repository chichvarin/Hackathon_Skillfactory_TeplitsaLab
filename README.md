# Hackathon_Skillfactory_TeplitsaLab
NGOs' data analytics
Identification of vulnerable populations

## Tasks
1. To cluster the regions of the Russian Federation and determine which of them are most in need of assistance to the poor / disadvantaged segments of the population.
2. Describe population groups facing poverty.
3. Determine the degree of influence on the level of poverty in the region by the number of children, pensioners and other socially vulnerable groups.

## Hypothesis
Intuitively, we believe that economic indicators, such as GDP per capita, income distribution, will have a significant impact on the poverty rates of the population living in a particular region. However, we would like to draw attention in our study to other signs that are indirectly related to poverty.

## Hypothesis testing
Statistical Tests
/ k-means
/ Hierarchical clustering (maybe)
/ t-SNE/PCA

## Summary
* Managed to load data from disparate sources, prepare it for merging and form the final dataframe for clustering.
* It was possible to find additional data on
  - utility bills
  - loan debt
  - entered square meters of living space
  - registered as in need of improvement
  - alcoholism
  - crime
* The success of the study was facilitated by the careful preparation of the names of the regions - the basis for the association.
The use of various types of visualizations made it possible to visualize the results of their work in various sections.
* After the main clustering, an additional analysis was performed by clusters. Interesting findings on alcoholism and drug addiction in economically prosperous regions.
* Useful findings on helping the elderly, even in economically prosperous areas.

## Outlook
* In a more explicit form, compare the results of different clustering algorithms (so far - one of the algorithms is simply useless),
but if a clear advantage of one of the algorithms over the other is shown, it makes sense to add other algorithms.
