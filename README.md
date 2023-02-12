# MarketBasketDemo
This repository is a demo of a market basket methodology using kaggle instacart data. The competition can be found using the following link: https://www.kaggle.com/c/instacart-market-basket-analysis

The data is not included within this repository due to size limitations but can be accessed by using the link above and navigating to the data tab.

The analysis can be found in the /scripts directory with the results found in /results. This was written in 2019 and since then there have been numerous advancedments within the R ecosystem to many of the packages used.

The focus of this R Markdown script is to teach a spin-off methodology of the apriori algorithm while maintaining attribution to enrich dashboarding tools such as PowerBI and Tableau. Apriori will generally condense the data in such a way that you will know item pairings but the algorithm itself tends to disgard any additional information. This methodology will essentially count pairings and keep attribution such as category, color, size, etc available for use elsewhere.
