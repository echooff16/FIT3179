# Best Universities: Global University Rankings Visualisation

An interactive web page that helps prospective students explore the world's top universities and the countries they are in, using 2024 global ranking data. Built for FIT3179 Data Visualisation at Monash University.

**Live site:** https://echooff16.github.io/FIT3179/

## Overview

Choosing a university abroad means comparing hundreds of institutions across dozens of countries. This project takes ranking data for over 1,000 universities, cleans it, and presents it as three interactive visualisations that answer two questions: which universities stand out, and which countries offer the strongest options.

## Visualisations

1. **Choropleth world map:** shows how the top 500 universities are distributed across countries.
2. **Interactive university analysis:** a filterable bar chart of the top 500 universities by country, showing total student numbers, international students and further details for each university.
3. **Country comparison:** a bar chart comparing the countries that host the top 500 universities.

## Data preparation

Ranking data for over 1,000 universities was sourced from [source, e.g. QS World University Rankings 2024] and cleaned using [tool, e.g. Python with pandas] to [e.g. standardise country names for map matching, handle missing values and convert student figures to numeric values].

## Tech stack

- Vega-Lite and Vega-Embed for the visualisations
- Bootstrap 5 for page layout and styling
- HTML and CSS
- [Python / Excel] for data cleaning
- GitHub Pages for hosting

## Running locally

Clone the repository and serve the folder with any local web server (for example `python -m http.server`), then open `index.html` in your browser. A local server is needed because the Vega-Lite specifications are loaded from separate files.

## Acknowledgements

Ranking data from [source]. Built for FIT3179 Data Visualisation, Monash University.
