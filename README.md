# Communicate-Data-Findings
Data Visualization Project for the Udacity Data Analytics Nanodegree

# Loans Data Exploration
## by Austin Mnthambala Jr.


## Dataset

The data consists of information regarding 113,937 prosper laons, including
prosper information, loan details, and other loan features. The dataset can be found in this amazon data store(https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv),
with feature documentation available at(https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings

In the exploration, I found that there was a strong relationship between the loan amount and the amount of investors who funded them, with modifying effects from the loan term, yearly Quarter and the year the loan was taken out. The relationship between loan amounts and investors is partially linear, as the loan amount increases the number of investors funding them decreases. When the loan amount is put on a logarithmic scale and the investors also put on a logarithmic scale, the loan amount is multimodal with no skew while the investors is right skewed with a unimodal distribution. The loan term and the yearly quarter are distributed unevenly with the Q1 and Q4 being the higher distributions while loan term is highest 36 month term and then drops for 60 and 12. According to the heatmap for Multivariate Exploration, through the years the number of investors who funded drastically spread out into funding higher loan amounts which meant more cases of more than 200 investors funding high loan amounts

Outside of the main variables of interest, I verified the relationship between loan term weight and yearly quarters. For the dataset given, there was an interesting interaction in loan terms where 36 month was the highest option but the relationship put against the loan amounts brings up a higher distribution for 60 months loan term.


## Key Insights for Presentation

For the presentation, I focus on the relationship between the investors, loan amount and the fiscal year and leave out most of the intermediate derivations. I start by introducing the loan amounts variable, followed by the investors distribution, then plot the heatmaps.
