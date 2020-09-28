# A-ZARS - ZARS for Analysis
A-Zars is a software completely written in Python for the analysis of reviews extracted from Online Travel Agencies (OTAs) through the [ZARS](https://github.com/alessiamns/ZARS) software. 

A-ZARS allows you to search for a service within the review using Machine Learning algorithms, perform sentiment analysis of the reviews and add the Geonames code to the locations of origin of the authors of the reviews. A-Zars is released under the GNU General Public License v 3.0.

## System requirements

* [Python 3](https://www.python.org/downloads/)
* [Xampp](https://www.apachefriends.org/download.html)
* [Chrome Driver](https://chromedriver.chromium.org/)
* [Jupyter](https://jupyter.org/)

Python libraries

* [Selenium](https://www.selenium.dev/downloads/)
* [MySQL connector](https://www.mysql.com/it/products/connector/)
* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)
* [Scikit-learn](https://scikit-learn.org/)
* [Googletrans](https://py-googletrans.readthedocs.io/en/latest/)
* [Langdetect](https://pypi.org/project/langdetect/)

## Installation

* Download zip from GitHub (https://github.com/alessiamns/A-ZARS) 
* Start Jupyter and run the notebooks

## Running the tests

* Download the file containing the reviews in JSON format

1. [Geonames_scraping.ipynb](Geonames_scraping.ipynb)

#### Arguments
> -place `[REQUIRED]`
> -pages `[OPTIONAL]`
> -pr `[OPTIONAL]`

2. [GeonamesId_association.ipynb](GeonamesId_association.ipynb)

#### Arguments
> read_json `reviews.json`

3. [Language_association.ipynb](Language_association.ipynb)

#### Arguments


4. [Translate_Reviews.ipynb](Translate_Reviews.ipynb)

#### Arguments
> -place `[REQUIRED]`


5. [Breakfast_Analysis.ipynb](Breakfast_Analysis.ipynb)

#### Arguments
> -place `[REQUIRED]`


