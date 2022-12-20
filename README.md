# Project Title

An Introduction to GeoPandas:
Missing Journalists World-Wide in 2021

<img src="images/CPJMissingSaved.png"/>

## Description

This project was initially a class assignment intended to introduce the GeoPandas library. While searching for data with spatial attributes that I could use to demonstrate the library, I thought of the Committee to Protect Journalists. The CPJ keeps a tally of some grim statistics - attacks on journalists around the world. On their site, you can view counts by year, or country, of journalists killed, detained, or simply missing.

I feel it's only appropriate, before getting into the details of GeoPandas, to acknowledge the sacrifices of the many dedicated journalists around the world who refuse to be intimidated or corrupted by autocratic or military regimes, or by criminal organizations.

## Getting Started

### Dependencies

The only library needed is GeoPandas.
```
pip install geopandas
```

### Data

The notebook uses two datasets:

* The CPJ data on journalists missing in 2021 by country, available here: https://cpj.org/data/
* The Economist Intelligence Unit democracy index for countries around the world. The index is a number from 0 to 100, based on several dozen indicators, expressing the quality of democracy in each country.

Both datasets are available in the 'data' directory of the repository.

### Images

The notebook has several images embedded within Markdown text cells. These are available in the 'images' directory of the repository.

GitHub has an issue with images embedded in Markdown cells. The images will appear in your development environment, but when the notebooks are pushed to a GitHub repository, only an icon is visible. The only workable solution I found was to upload them to a Google Drive with public viewing permission, then reference them using the URL in the notebook. Well, not exactly using the URL; I used the steps outlined in this Medium article:
https://medium.com/analytics-vidhya/embedding-your-image-in-google-colab-markdown-3998d5ac2684

## Authors

Ali Tobah
tobah@umich.edu

## License

Free for personal or educational not for profit use. Otherwise, please contact the author.  Please indicate the source in any case.
