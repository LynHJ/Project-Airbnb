# Project-Airbnb


## Project
Project Topic:Share Economy

Team Member:Nick Carr,Bharat Guturi,Lin Huan Jhe

Introduction:

The share economy has quickly become a big part of our life and is continuing to grow and innovate industries at a rapid rate. We have decided to gain more insight into the use of Airbnb in Perth metropolitan area. Our end goal is to find out which areas are the most sought out places to stay, how long people stay in these areas and what is an expected price to pay for these places.

### Source

Our data was collected from http://insideairbnb.com/western-australia in which we cleaned the data to ensure we were only using columns that were going to allow us to ask and find answers from our data. Our focus accommodation type is entire house/apartment and private rooms, as these two types of accommodation make up roughly 98% of the Perth metropolitan market. 


### Questions
1.Which suburbs are the most popular to stay, based on the numbers of reviews? What factors may cause this?
2.Are there any correlations between occupancy and price?
3.What is the average price between short, medium and long-term stays?
4.What price should I advertise the property to ensure I get a booking?



## Content:
Project
|
|-InputData:|-neighbourhoods.csv
|          |-listings.csv
|          |-reviews.csv
|-OutputData:|-avg_price_entire_apt.csv
|           |-avg_price_private_room.csv
|           |-Price(Heatmap).png
|           |-TotalReviews(Heatmap).png
|-Final.ipynb
|-Presentation_file.txt
|-Project Draft.docx
|-README.md

## Installation
1.conda env create -n PythonData --file intro_python_requirements_osx.yml python=3.7
2.pip install notebook
3.jupyter nbextension enable --py --sys-prefix widgetsnbextension
  conda install -c conda-forge gmaps
  jupyter nbextension enable --py --sys-prefix gmaps
4.conda install matplotlib  
  

## Prerequisites
Get a free API Key at https://cloud.google.com/maps-platform/
Clone the repo
git clone https://github.com/your_username_/Project-Name.git
Create a api-keys.py to put your API in
gkey = 'ENTER YOUR API'

Appendix/Reference
1.http://insideairbnb.com/western-australia
2.https://www.stratosjets.com/blog/airbnb-statistics/
3.https://www.businesswire.com/news/home/20220617005279/en/Global-Online-Food-Delivery-Services-Markets-2022-2026-2031-with-takeaway.com-Doordash-Deliveroo-Uber-eats-Zomato-Dominating---ResearchAndMarkets.com#:~:text=The%20market%20is%20expected%20to,(CAGR)%20of%205.6%25.
4.https://www.stratosjets.com/blog/airbnb-statistics/

