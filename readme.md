# Gnod Music Recommender System

## Project Overview

The Gnod Music Recommender System is an advanced music recommendation engine that aims to enhance the user experience on the Gnoosic platform. The goal is to provide song suggestions not only based on collaborative filtering algorithms but also considering acoustic similarities and global popularity trends.

## Features

- **Collaborative Filtering**: Leveraging user data to suggest bands and songs that align with their tastes.
- **Acoustic Similarity**: Recommending songs that match users' preferred acoustic profiles.
- **Trending Tracks**: Identifying and recommending songs that are trending worldwide.

## Data Collection

This project utilizes web scraping to gather data on current popular songs from various online charts. The initial phase focuses on extracting song titles and artists from [Popvortex](http://www.popvortex.com/music/charts/top-100-songs.php) and [Billboard Hot 100](https://www.billboard.com/charts/hot-100/), storing the information in pandas dataframes for further analysis.

## Clustering Analysis

Post data collection, the project will implement clustering algorithms to group similar songs, facilitating targeted recommendations to users based on their input.

## Tools and Technologies

- **Python**: Primary programming language for data collection and analysis.
- **Pandas**: Data manipulation and analysis.
- **BeautifulSoup**: Web scraping library to extract data from web pages.
- **Requests**: HTTP library for Python to send HTTP requests.

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/Abelenva/Web-scraping-portfolio.git
