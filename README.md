# data-science-blog-post

## Motivation
Airbnb is one of popular and widely spread stay provider across the world. It generates a most of its revenue from US and Boston is one of the popular Airbnb destination in US. Analyzing its data is one the useful way to know the trends and its offereing in Boston.

The project uses CRISP-DM process to analyse the dataset. Following questions intrigued me:

1. Which neighborhood of Boston has more listings? What type of properties are provided there?
2. What is the availability of the listings across each neighborhood and their review/responsiveness?
3. What is the price trend among the neighborhood throughout the year? what is the weekend price trend?
4. Which amenities, in general, can you expect and what are some rare amenities, and how much extra do you have to pay to get those?
5. Which neighborhood is recently seeing a surge in listings?

The answers to these questions along with suitable visualization is discussed in the article [here](https://medium.com/@kumarsantosh04/things-to-consider-before-planning-your-trip-to-boston-d4acdc26b136). You can also see [the notebook](boston-airbnb.ipynb)


## Install requirements:

Run the following commands in the project's root directory to install dependencies

~~~
pip install -r requirements.txt
~~~

Also install jupyter-notebook for running the boston-airbnb.ipynb.

## Instructions:

Run the following commands in the project's root directory.

~~~
jupyter-notebook
~~~       

http://localhost:8888 will open, open the boston-airbnb.ipynb and start running each cell one by one.

## Project Structure:
~~~
- data
|- Boston_Neighborhoods.geojson # geojson files of boston neighbourhoods
|- calendar.csv  
|- listings.csv
|- reviews.csv 
|- README.md
|
- boston-airbnb.html
- boston-airbnb.ipynb
- README.md
- requirements.txt
~~~
## Project Components:
The data folder contains all the data used for the analysis and the ipynb contains all the code.

## Acknowledgement

AirBnb for providing the data for analysis
