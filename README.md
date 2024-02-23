# Replication of Democratization and Linguistic Complexity: The Effect of Franchise Extension on Parliamentary Discourse, 1832-1915

>Abstract: We consider the impact of the Second Reform Act, and the doubling of the electorate it delivered, on the linguistic complexity of speeches made by members of parliament in Britain. Noting that the new voters were generally poorer and less educated than those who already enjoyed the suffrage, we hypothesize that cabinet ministers had strong incentives—relative to other members—to appeal to these new electors with simpler statements during parliamentary debates. We assess this claim with a dataset of over half a million speeches for the period between the Great Reform Act and Great War, along with methods for measuring the comprehensibility of texts— which we validate in some detail. The theorized relationship holds: ministers become statistically significantly easier to understand (on average) relative to backbenchers, and this effect occurs almost immediately after the 1868 election. We show that this results is not an artifact of new personnel in the House of Commons.

The full original research paper can be found [here](https://www-jstor-org.proxy.library.georgetown.edu/stable/26550694?seq=8)

## Tutorial 
The R codes used for this replication can be found in the **code** folder. The dataset provided by Spirling's research team can be found in the **data** folder. The visualizations outputted by from the code can be found in teh **outputs** folder. 

## Codes
- `Replication.Rmd`: this code replicates each of the figures found in the original research paper using the recalculated FRE score. There is also an extension that evaluates how other complexity measures score three sample sentences from the corpus.
- `Replication_updated.Rmd`: this code recreates figures 1, 2, 3, 4, and 6 using the 'tidyverse' and 'ggplot' packages instead of base R.

## Data
Includes both the rdata and csv version of the dataset.
