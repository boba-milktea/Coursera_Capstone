# IBM Applied Data Science Capstone - The Battle of the Neighborhoods

This project is part of the IBM Data Science Professional Certificate on Coursera. It focuses on analyzing data from the Greater Taipei area to identify the best locations for opening a new venue, such as a restaurant, based on factors like population density, economic diversity, and existing venues.

## Table of Contents
- [Project Overview](#project-overview)
- [Files and Resources](#files-and-resources)
- [Data Collection](#data-collection)
- [Methodology](#methodology)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Conclusion](#conclusion)

## Project Overview
Taipei is one of the most densely populated cities in the world, and it presents significant business opportunities for new venues. The goal of this project is to explore the best districts in Greater Taipei for opening a venue by using data analysis and machine learning techniques. The project involves determining which districts have the highest population density, economic diversity, and business potential.

Key questions explored:
1. Which districts have the highest population density?
2. Which districts have the best economic diversity?
3. Which districts have the most potential for new businesses?

## Files and Resources

The repository includes the following files:

- **`README.md`**: This file contains the project description and setup instructions.
- **`The Battle of the Neighborhoods I.ipynb`**: The Jupyter notebook for Week 1, where data collection and initial exploration were done.
- **`The Battle of the Neighborhoods II.ipynb`**: The Jupyter notebook for Week 2, focusing on data processing, visualization, and clustering.
- **`The Battle of the neighborhoods.pdf`**: The final report summarizing the project findings and analysis.
- **`The Battle of the neighborhoods_PPT.pdf`**: A presentation summarizing the results of the analysis.

## Data Collection
The data used in this project includes:
- **Geographic Data**: Collected from Taiwan’s government data platform and Wikipedia for municipal information.
- **Venue Data**: Retrieved via the Foursquare API to analyze existing venues in the districts.
- **Demographic Data**: Scraped and processed from Wikipedia and government platforms.

## Methodology
1. **Data Cleaning**: Using Python's `pandas` library to clean and organize the demographic data.
2. **Population Density Analysis**: Population density was calculated for each district, and geographic data was visualized using the `folium` library.
3. **Venue Data Analysis**: Venue data was collected from Foursquare API, categorized, and analyzed using K-means clustering to identify areas with diverse economic activity.
4. **Clustering**: K-means clustering was applied to group the districts into 8 clusters based on their venue types. The elbow method helped determine the optimal number of clusters.

## Results
The project identified several key findings:
- **Yonghe** and **Daan** were found to have the highest population density.
- **Banqiao** and **Daan** exhibited a diverse mix of economic activities, making them ideal for new businesses.
- The clustering analysis highlighted 8 distinct groups of districts based on the types of venues.

## Technologies Used
- Python
- Jupyter Notebooks
- Pandas
- Folium
- GeoJSON
- Foursquare API
- K-means Clustering (Scikit-learn)

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/boba-milktea/Coursera_Capstone.git
2. Install the required Python libraries:
   ```bash
   pip install pandas folium geopy requests sklearn
3. Open the Jupyter notebooks to explore the project:
   ```bash
   jupyter notebook
4. Run the notebooks to see the analysis and results.
