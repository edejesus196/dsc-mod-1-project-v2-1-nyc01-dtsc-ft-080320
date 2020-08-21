## Movies Industry Analysis Project

Flatiron Module 1 Final Project by Edward De Jesus

## Project Overview & Business Case

Scenario: Microsoft is interested in entering the movie business to establish the company as a leader in film production capabilities and to gain additional profits. We have been tasked with gathering and analyzing movie data to provide the company with insights and recommendations. I aim to answer the following questions:

- What type of films are most likely to be profitable profits earned in recent years?
- What genres and sub genres are most profitable?
- How film genres have performed over the past decade?

## Approach

- Review available data sources
- Obtained data from The Numbers Movie Database
- Web scraped data from Box Office Mojo using request HTML
- Cleaned and merge datasets
- Visualize data using Plotly libraries.

## Review available data sources

I reviewed the original datasets provided with the project to determine what data I was missing and help guide on where to search for data next. I realized I was missing more recently box office numbers and need for categorical information to help determine which types of films are more successful.

## Obtained data from The Numbers Movie Database

I discovered the The Numbers Movies database. This database contained both financial and categorical information I need to help answer my questions. After inquiring about API request, I realized that The Numbers charged for access to their entire dataset. However, I was provided with a free CSV file via email containing over 1,900 rows of movies data from 2006 to 2018.

## Web scraped data from Box Office Mojo using request HTML

I successfully web scrapped the Box Office Mojo website using request HTML. I was able to scrape for additional financial information from 2010 to 2020.

## Cleaned and merge datasets

I used the panda’s library to clean data, removing null values and merging different datasets with common columns. I also manipulated the date to group the data by genres, and sub genres and to calculate the profits for each group.

## Visualize data using Plotly libraries.

I used Plotly's libraries to help visualize the information I had gathered with the data. I also created appealing plots with a consistent theme for the presentation.

Link to pdf slides: [blue_text](https://drive.google.com/file/d/1imRRrwBnt78CSwnmIpuQZSVq77yI-7Xf/view?usp=sharing)