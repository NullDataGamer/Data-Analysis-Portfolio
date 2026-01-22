# Steam Game Data (2021-2025) Analysis Project
## Project Kickoff
When trying to decide what to do for my first project I couldn't think of any good ideas.
As I was browsing Kaggle I came across the following dataset (https://www.kaggle.com/datasets/jypenpen54534/steam-games-dataset-2021-2025-65k). 
This dataset really stood out to me for multiple reasons the main ones being.

  1) It is a topic I am knowledgable and passionate about.
  2) It is a very large versatile dataset I could manipulate to extract insights.
  3) The data was collected from the source making it an accurate source.

![Kaggle homepage](Kaggle%20homepage.png)


## Project Progression
### Data Cleaning

Now I had a dataset and an idea of what I wanted to do I made quick work downloading and investigating the viability of the data.
I found that the dataset was very useable it would just need cleaning as multiple instances of missing values, Null values or inconsistent entries.
After cleaning the data by removing blank entries, resolving data format issues I decided to add conditional columns to allow for more in depth analysis.
The columns I wanted to add the most were the following;

  1) Season of release
  2) Price bands

With those conditional columns created it would allow me to create slicers to break the data down further later on.
Once I was done cleaning and transforming the data I could finally begin visualising and analysing the data.

### Data Visualisation

I decided to start with a universal chart that I could use as a baseline to make sure any other charts created didn't give anomalous answers.
The first chart created was a simple bar chart showing the 25 most popular games released during the timeframe shown below.

![Graph 1](Graph%201.png)

The other basic charts that I wanted to display were the number of recommendations each season gets.
I wanted to see if there was a trend or pattern for example less recommendations in the summer but more during winter.
I felt the best way to demonstrate this was with a pie chart which is displayed below.

![Graph 2](Graph%202.png)

Another basic chart I created was to see if there was a trend between the price of a game and its popularity.
To get this I created a basic scatter plot with the game price on the X axis and popularity on the Y axis before adding a trend line.
This chart would give me a basic insight into the general trend of popularity of games based on price as shown below.

![Graph 3](Graph%203.png)

I created a few more graphs all the basic graphs for my intial data break down were the following;

  1) 25 Most popular games ​
  2) All games popularity by price (With trendline)​
  3) 25 Most popular games by price ​
  4) Game popularity by season​
  5) 25 Most popular games by year

## Basic Analysis Of These Graphs

Once I was able to visualise the data presented by the graphs I was given an intial insight into the data.
The initial takeways I was provided with was that;

  1) $60 Games were the most popular.
  2) Winter would be the best month to release a game.
  3) The year of release doesn't impact much.

Despite these findings seeming to be accurate I wanted to verify this further as data can be misleading.
To do this I decided to create some dashboards with interactive filters to allow a deeper dive into the data.
This was the reason I created the conditional columns earlier as I wanted my main slicers to be for season and price bands.

## Dashboard Creation

To break down the data further to verify if my previous findings were accurate or missleading I created the following dashboards.

### 1) 25 Most popular games (with slicers for season and price range)

![Dashboard 1](Dashboard%201.png)
​
### 2) 25 Most popular games by price (with slicers for season and price range)
  
![Dashboard 2](Dashboard%202.png)  
  ​
### 3) Game popularity by season (with slicer for year and cards to display the 3 most popular games and the sum of recommendations for them along with a count of the number of games released)
  
![Dashboard 3](Dashboard%203.png)    
  ​
### 4) 25 Most popular games by year (with slicers for season and price range)

![Dashboard 4](Dashboard%204.png)  

## Final analysis



