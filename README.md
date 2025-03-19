# Movies Popularity

## Project Summary

The "Movies Popularity" project is a comprehensive analysis of movie data, focusing on the relationship between popularity and critical acclaim.
By leveraging The Movie Database ([TMDb](https://www.themoviedb.org) API and web scraping techniques, the project compiles a rich dataset of movies from various languages and countries, spanning from 2000 to the present. The analysis includes visualizations that explore trends in movie popularity, the distribution of prestigious awards, and the interplay between audience appeal and critical recognition.

### Purpose of the Project

The primary goal of this project is to uncover insights into what drives movie popularity and how it correlates with awards and recognition.
By examining a diverse set of movies, the project aims to identify patterns in movie production, audience preferences, and the impact of awards on a film's success.
This understanding can inform strategies for filmmakers, marketers, and industry analysts seeking to maximize the impact of their productions.

### Story Behind the Project

We embarked on this project out of a shared passion for cinema and data analysis.
Inspired by the rich history and cultural significance of films, we sought to explore the factors that contribute to a movie's success.
Through meticulous data collection and analysis, we wanted to uncovered fascinating trends and insights, shedding light on the complex dynamics of the film industry.
Our journey involved overcoming challenges related to data scraping, cleaning, and visualization, ultimately leading to a deeper appreciation of the art and science behind movie popularity.
This project not only provides valuable insights but also serves as a testament to the power of data in understanding and appreciating the world of cinema.

# Data-Harvesting

## About This Project

This repository contains the final project for the **Data Harvesting** course in the **Master in Computational Social Sciences at Universidad Carlos III de Madrid**.
The project focuses on collecting and analyzing movie popularity data using **The Movie Database (TMDb) API** and scraping award-winning films from Wikipedia.
The goal is to explore trends in movie production, language distribution, and award recognition patterns.

This repository is maintained by **Ekin Kızıldaş** and **Aurora Sterpellone**.

## Repository Structure

This repository includes the following files:

- `Final Project.Rmd`: A fully replicable script that details the process of data collection and analysis.
- `README.md`: This document, providing an overview of the project.
- `final_data.csv`: The processed dataset containing the final movie data.
- `.gitignore & gitignore.txt`: Files to manage ignored files in the repository.
- `.Rhistory`: Contains R command history.
- `.DS_Store`: A system file automatically generated on macOS.

## Requirements and Reproduction Guide

To reproduce this project, you need **RStudio** installed and a valid **API key from The Movie Database (TMDb)**.

### Obtaining a TMDb API Key

1. Visit [TMDb API](https://developer.themoviedb.org/docs/getting-started).
2. Sign up or log in.
3. Navigate to the **API section** and generate an API key.
4. Store the API key safely, as it will be required to fetch movie data.

## Running the Project

To execute the project, follow these steps:

1. Clone or download this repository and unzip it if necessary.
2. Open **Final Project.Rmd** in RStudio.
3. Run the script **chunk-by-chunk**, following the explanations in the comments.
   - Securely store your API key.
   - Define the range of years and languages for movie collection.
   - Retrieve movie details and release dates from TMDb.
   - Scrape award-winning movie data from Wikipedia.
   - Process and clean the collected datasets.

Each script contains markdown explanations and inline comments to guide you through the methodology and code structure.

By following these steps, you can replicate the full workflow and analyze movie trends and award distributions.

---

🎬 **Happy Analyzing!** 🍿