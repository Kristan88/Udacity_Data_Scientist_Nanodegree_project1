
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Required libraries:

pandas
numpy
seaborn
matplotlib

The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

The motivation of this blogpost was to analyse how the selling of traditional  cars with internal combustion engines evolved over the years in Europe to learn what engines types will likely be disappeared or loose its volume in the market, and which ones are rising.
For my study I used new passenger car registration and gdp datasets from Eurostat database.

1. How new car registration evolves over years and are there any observable trend at different countries?
2. Does Europe says goodbye to diesel engines?
3. Which engine sizes are the most popular for both diesel and petrol cars?
4. How the number of new cars correlates to GDP?


## File Descriptions <a name="files"></a>

There are 1 Jupyter notebook available here to showcase work related to the above questions. 
There are 2 excel files I used for the analysis. The original TSV files were downloaded from here: https://ec.europa.eu/eurostat/data/database

## Results<a name="results"></a>

We saw that selling new cars in European countries change dynamically depending on the economic situation.
Diesel passenger cars were very popular in many countries from the early 2000's until circa 2014/2015.
After that in almost all countries petrol cars gained back its priority(also hybrid and electric cars started to be sold significantly everywhere).
In Italy, Germany and Finland the number of new petrol cars with engine size between 1400–1999 cc are rising rapidly.
In Finland petrol cars with large engines (above 2000 cc) are also getting more and more popular.
New car registration has strong positive correlation with GDP.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Eurostat for the data.  All files I used for the anlysis were downloaded from here: https://ec.europa.eu/eurostat/data/database
You can read more about Eurostat from here: https://ec.europa.eu/eurostat/web/main/home
