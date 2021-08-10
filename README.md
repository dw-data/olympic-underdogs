# Discovering the (mostly) unsung heroes of Tokyo 
This repository contains the data and source code behind the analysis for the published at DW.

It was written by  Rodrigo Menegat and Eva Lopez.

## Data

The data source for this story is the work of a group of Olympic historians that currrently publish in-detph statistics at [Olympedia](https://www.olympedia.org/static/about) -- and, formerly, at the now inactive [OlympicsReference](https://www.sports-reference.com/olympics.html) website.

It was originally collected by [Randi H. Griffin](https://www.randigriffin.com/) in June 2018 and published as a [Kaggle dataset](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results). 

The file linked above was the starting point for the analysis. Its accuracy was confirmed by comparing a sample of the data with Olympedia's current website. However, due to the shifting nature of Olympic records, there are some noteworthy exceptions. 

For instance, when the dataset was first collected, a 2008 bronze long jump medal was still awarded to the Russian athlete Tatyana Lebedeva. However, in July 2018, [she had to return her award due to a doping conviction](https://www.espn.com/olympics/story/_/id/24197219/russians-tatyana-lebedeva-maria-abakumova-stripped-2008-olympic-medals). 

The original file won't show this correction, but all the figures mentioned directly in our story take similar cases into account. If a number is mentioned there explicitly, then it was double checked against those changes. This was not done with the entire dataset, though, and one might find similar incosistencies while browsing it. Nevertheless, they are minor exceptions and won't affect the overall conclusions drawn by the text.

It's also noteworthy that statistics for the Olympic Games of the first half of the 20th century are often precarious, with numbers changing according to the source used. The 1900 Olympics is a good example of this issue: the Games were held as part of the 1900 Paris World Fair, and to this day there is disagreement about which contests were actual Olympic competitions and which were demonstration sports presented at the broader exposition.

The data has already been used for a DW story on [gender balance](https://github.com/dw-data/gender-olympics), and was updated after the last medals of the 2020 Olympics were awarded.

## Repository structure

The files in this repository are divided in the following subdirectories:

- `data`: contains the raw data used on the data analysis and consists of three csv-files ("all-competitors", "totals-by-year", "victory-ratio"
- `output`: containts the processed data, summarizing the results of the analysis, which was used for making the data visualizations.
