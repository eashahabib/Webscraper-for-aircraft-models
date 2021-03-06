# Webscraper For Aircraft models 
The purpose of this repository is to scrape differenet multiple aircraft directories online to compile into a single resource. This can then be used in a ML model to predict certain aircraft features for new aircrafts. 

## Content
The code consists of 2 files:
* scraper.py
* functions.py

The scraper.py file contains the main code that can be run to scraoe the data. The functions.py consists of all the function definitions and classes required by scraper.py
The reason for having 2 scripts is to improve code readability and code testing. 

The 'Project Brief.ipynb' includes the requirements of this project along with additional recommended functionalities. 
The 'project_notebook.ipynb' was a  testing notebook used for unit testing different parts of the code. 

### Data
The data is outputted into an excel file called output, with different sheets for different sources. The 3 sources used are:
* Airliners (https://www.airliners.net/aircraft-data)
* Aircraft Bluebook (https://aircraftbluebook.com/Tools/ABB/ShowSpecifications.do)
* Aircraft Performance Data by EuroControl (https://contentzone.eurocontrol.int/aircraftperformance/default.aspx?)

## How to use this?
Once the scraper.py is run, it will export an excel file with all the scraped data, along with an SQL database which can be used to extract more meaningful relations between the data. 

### Packages Required:
- requests
- time
- pandas
- sqlalchemy
- tqdm
- selenium
- os.path

## Work in Progress
* Missing data entries needs to be either removed or completed
* Data cleaning needs to be implemented
