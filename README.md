# National Parks Visitation Analysis

This project explores visitation trends for U.S. National Parks from 1904 to 2016. Using the provided dataset, it analyzes visitation patterns, regions, states, and individual parks to optimize park visit plans. The project incorporates clustering and route optimization techniques to create a practical itinerary for exploring multiple parks in a single trip.

---

## Project Overview

### Goals:

1. Explore and clean the U.S. National Parks visitation dataset.
2. Visualize trends in visitation over time and across regions.
3. Identify the most popular parks based on visitation numbers.
4. Optimize park visits through clustering and the Traveling Salesman Problem (TSP).

### Key Components:

- **Data Cleaning**: Handling missing values and converting data types for analysis.
- **Visualization**: Using ggplot2 and usmap to create line plots, heatmaps, and clustered maps.
- **Clustering**: Employing hierarchical clustering to group parks into clusters and subclusters.
- **Route Optimization**: Using TSP and mapping libraries to find the most efficient routes for visiting parks.

---

## Technologies and Tools Used

- R Programming: Data manipulation, visualization, and modeling.
- Packages:
  - Data Handling: dplyr, tidyr, stringr, readr
  - Visualization: ggplot2, gridExtra, usmap, sf, scales, gganimate
  - Clustering: TSP, cluster
  - Routing: httr, jsonlite, geosphere
- Markdown: Documentation and project write-up.
- GitHub: Repository hosting and version control.

---

## Project Workflow

### Data Exploration

- Dataset: U.S. National Parks Visitation (1904–2016).
- Steps:
    1. Load and inspect the dataset.
    2. Identify and address data issues (e.g., missing values, inconsistent formats).
    3. Subset relevant columns for analysis.

### Visualizations

- Visitation Trends:
  - Total visitation per year.
  - Regional trends using facet plots.
- State-Level Analysis:
  - Heatmap of total visitation by state.
- Park-Level Analysis:
  - Bubble plot highlighting the most visited parks.

### Clustering

- Perform hierarchical clustering to group parks into clusters based on geographic proximity.

### Route Optimization

- Apply the TSP to find the shortest route for visiting parks within each cluster.

---

## Results

1. Visitation Trends:
    - Overall visitation has increased since 1904
    - Pacific West and Intermountain regions saw the steepest increases in visitation.
2. Heatmap:
    - States like California, Wyoming, and Washington have the highest total visitation.
3. Cluster Analysis:
   - Parks were grouped into five main clusters based on geographic proximity.
4. Optimized Routes:
    - TSP provided efficient routes for visiting parks within clusters and subclusters.

---

## Future Work

- Use subclusters to refine routes further.
- Incorporate additional datasets for park features (e.g., terrain, amenities).
- Perform sentiment analysis on park reviews to understand visitor preferences.
- Create an interactive dashboard for route planning and visitation trends.

---

## Acknowledgments

- Data Source: [data.world](https://data.world/inform8n/us-national-parks-visitation-1904-2016-with-boundaries/workspace/file?filename=All+National+Parks+Visitation+1904-2016.csv)
- Inspiration: Visiting National Parks.

---

## Contact

For questions or suggestions, please reach out via [GitHub Issues](https://github.com/cdcoonce/National_Parks_Project/issues).