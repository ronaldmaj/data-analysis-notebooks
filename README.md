# data-analysis-notebooks
An assortment of Jupyter Notebooks where I have conducted some form of data analysis

## POLA Project 1, 2, 3, 4

The aim is to count the number of container ships in the port over the months in 2018 and compare with prior years.
The count can be compared against other data sets to have a baseline economic activity indicator. 
Afterwards, this can be used to reveal economic details about unknown nations, states or territories.
Data sources used:
Using the Planet API to obtain medium resolution satellite images of the Port of Los Angeles through Open California - Project 1
https://www.planet.com/products/open-california/
Processing the satellite images to remove unusable data - Project 2
Training a model to identify ships in a 80x80 box, using the labelled dataset the Kaggle dataset below - Project 3
https://www.kaggle.com/rhammell/ships-in-satellite-imagery
Comparing the container data with the number of container ships to find relationship between the two, therefore economic activity. Used the statistics provided on the Port of Los Angeles website - Project 4
https://www.portoflosangeles.org/business/statistics/container-statistics/historical-teu-statistics-1996

## Economy_Sun_Spot_relationship.ipynb
Analysis of 25 economic indicators for 17 countries from 1870 - 2016 with sunspot numbers over the same period.
Data is sourced from:
http://www.macrohistory.net/data/ (Global economic data)
http://www.sidc.be/silso/datafiles (Sunspot data)
