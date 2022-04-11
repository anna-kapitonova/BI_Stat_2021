## Project 2. Data analysis of protein expression in the mouse model of Down syndrome.

In 2015 [Ahmed and collegues](10.1371/journal.pone.0119491) investigated protein dynamics associated with failed and rescued learning in the Ts65Dn mouse model of Down syndrome.

Here I analysed available data from this research (could be downloaded [here](https://archive.ics.uci.edu/ml/datasets/Mice+Protein+Expression#)):

The report contain the following parts:

1. **Dataset description (5 points)**
- how many mice were studied?
- what groups can you describe?
- are the groups balanced?
- how many missed values data cotain? (NA)
2. **Are there any differences in the level of BDNF_N production depending on the experimental class? (10 points)**
3. **Try to build a linear model, that can predict the level of ERBB4_N production by other proteins data (15 points)**
- examine the model
- explain why it is a good/bad solution
4. **PCA (15 points)**
- ordination
- plots of factor loadings
- find out, what percent of the data each component explain
- 3D plot for first three components
5. **The search for differentially expressed genes (proteins) using DESeq2 - creative part of the task (15 points).**
