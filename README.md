# Discovering the (mostly) unsung heroes of Tokyo 
This repository contains the data and source code behind the [analysis](https://www.dw.com/en/tokyo-olympics-uncovering-the-unsung-heroes-with-data/a-58820652) for the published at DW.

It was written by  Rodrigo Menegat and Eva Lopez.

## Data

The data source for this story is the work of a group of Olympic historians that currrently publish in-detph statistics at [Olympedia](https://www.olympedia.org/static/about) -- and, formerly, at the now inactive [OlympicsReference](https://www.sports-reference.com/olympics.html) website.

This source has already been used for a DW story on [gender balance](https://github.com/dw-data/gender-olympics) published prior to the Tokyo Olympics. For this particular story, new data was collected as soon as the 2021 games were over.

At the time this history was written, however, Olympedia's website wasn't completely updated with all of the Tokyo Olimpics' results. The data for the missing events was then collected manually according to IOC's official result sheets.

## Repository structure

The files in this repository are divided in the following subdirectories:

- `code`: contains one Jupyter Notebook with the step-by-step analysis in which the story is based on.
- `data`: contains the raw data used on the data analysis and consists of two csv-files ("all-competitors" and "missing-events-at-080821"). The first consist of data collected directly from Olympedia, while the second contains the data collected from the IOC result sheets.
- `output`: containts the processed data, summarizing the results of the analysis, which was used for making the data visualizations.
