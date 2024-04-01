# NBA Player Stats Explorer

## A web app developed using Python and Streamlit for scraping NBA player stats through data filtering.

The NBA Players Stats Explorer is an interactive tool designed to allow users to explore and compare NBA player statistics.

This project accesses data from the NBA Stats website and the NBA Stats API to create a dataset containing player information, team information, and various statistics (e.g., points, rebounds, assists, etc.). 

Additionally, the program scrapes player stats pages from Basketball-reference.com to augment the dataset.

## User Interaction

- Left side we have a sidebar for user input where the user can select "Year", "Team", and "Position".

- Now, we can see detailed statistics for individual NBA players.

- Below the above section we also have options for "Download CSV file" and "Intercorrelation Heatmap"


## Dashboard

<img width="821" alt="Screenshot 2024-04-01 at 02 48 56" src="https://github.com/therealadnan/nba-explorer/assets/72304577/d35ec787-cbf0-48c3-a706-3fa0f9a73215">


## Heatmap

Clicking on the "Intercorrelation Heatmap" you can see the Heatmap of the selected Teams which can be used to perform exploratory data analysis.
<br />
<br />



<img width="819" alt="Screenshot 2024-04-01 at 02 49 25" src="https://github.com/therealadnan/nba-explorer/assets/72304577/08c5d6ec-85b6-4341-85c5-499995e968e1">


## Pre-requisites

The NBA Players Stats Explorer relies on the following Python packages:

- matplotlib==3.5.1
- numpy==1.21.5
- pandas==1.3.5
- seaborn==0.11.2
- streamlit==1.3.0
- lxml==4.7.1

## How to run

This app is built with Streamlit. To Run This Application in localhost;

"streamlit run Basketball-app.py"


