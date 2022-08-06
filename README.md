<div align="center">

# Dataset construction of Dutch House Prices

![Badge](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![Badge](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=Selenium&logoColor=white)
![Badge](https://img.shields.io/badge/-BeautifulSoup-informational?style=for-the-badge)

![Badge](https://img.shields.io/github/languages/code-size/bryanlusse/HousePrices__Webscraper)
![Badge](https://img.shields.io/github/languages/count/bryanlusse/HousePrices__Webscraper)
![Badge](https://img.shields.io/github/last-commit/bryanlusse/HousePrices__Webscraper)

[Overview](#scroll-overview)
•
[How to use](#chart_with_upwards_trend-model)
</div>

## :bookmark_tabs: Menu

- [Overview](#scroll-overview)
- [How to use](#chart_with_upwards_trend-model)
- [Requirements](#exclamation-requirements)
- [Folder Structure](#closedbook-results)
- [Author](#smiley_cat-author)

## :scroll: Overview

This folder hosts a projects that uses a programmed web bot to retrieve information on houses from [Funda](https://www.funda.nl/). The code has been used for the creation of a dataset of house prices on [Kaggle](https://www.kaggle.com/datasets/bryan2k19/dutch-house-prices-dataset).

This code can be used as an example of how to retrieve data from Funda, or can be used as an example of web scraping in general.

## :closed_book: How to use

Clone the repository by running the following command in terminal:

```console
$ git clone https://github.com/bryanlusse/HousePrices__Webscraper.git
```

Or just download the zip file at the top of the page.

Change your working directory and set up a virtual environment, by creating it and installing all the requirements:

```console
$ cd web_scraper
$ python -m venv venv
$ pip install -r requirements.txt
```

Activate your virtual environment and start up Jupyter Notebook. Select the *scraping.ipynb* file and you can code away and create your own web scraper!

```console
$ source venv/bin/activate
$ jupyter notebook
```

## :exclamation: Requirements

Found in [requirements.txt](https://github.com/bryanlusse/HousePrices__Webscraper/blob/master/web_scraper/requirements.txt).


## :open_file_folder: Folder Structure

```
.
├── assets                                   # Images for notebook
├── scraping.ipynb                           # Main notebook
├── requirements.txt                         # Required packages
└── README.md
```

## :smiley_cat: Author

- [@bryanlusse](https://github.com/bryanlusse)

Made with &nbsp;❤️&nbsp;