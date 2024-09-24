🌍 Global Temperature Trends Interactive Dashboard
This repository contains an interactive dashboard built with Plotly Dash that visualizes global temperature trends using data from the Global Land Temperatures by Major City dataset. This project demonstrates how we can utilize historical temperature data to explore climate patterns across the world and identify countries that may offer more moderate climates in the future.

🔍 Project Overview
The dataset used in this project spans from the 1700s to 2013, offering a rich historical context for global temperature changes. The dashboard consists of two primary components:

Map View: A global, interactive map that displays average temperatures by city, utilizing Plotly’s scatter_geo. Users can explore how temperature trends evolve across different cities and regions over time. An animation slider allows for an intuitive timeline exploration, showing temperature changes from past centuries up until 2013. Each city is represented by markers whose color indicates the average temperature and the size of the marker is determined by the absolute value of the temperature, ensuring colder regions remain visually distinct.

Best Countries for Future Living: This scatter plot highlights countries with moderate average temperatures, which may offer a more livable climate in the future. Canada, Russia, and Chile are specifically highlighted in this view to demonstrate how regions with temperate climates today could play a crucial role in future climate resilience. These countries are marked with larger markers and additional visual emphasis using an outlined border to ensure they stand out from other regions.

💡 Key Features
Dynamic Animation: The Map View utilizes Plotly's animation capabilities to provide a smooth transition between years, allowing users to track how temperatures have shifted globally over time. This enables an interactive experience where users can visually understand how the earth’s climate has changed across centuries.

Interactive Map: Users can hover over individual cities to see detailed temperature information. The map is projected using the natural earth projection for a clear and engaging view of global data.

Highlighted Insights: The Best Countries for Future Living view is designed to give users a quick glance at which countries might offer more favorable climates in the future, particularly in light of growing global concerns over climate change.

📊 Data and Methodology
The dataset, Global Land Temperatures by Major City, was sourced from Kaggle’s Climate Data Repository. It contains temperature readings from various cities around the world from the 1700s to 2013. For the purposes of this dashboard:

We cleaned the data by removing rows with missing temperature values.
The dataset was aggregated by year to provide a high-level view of temperature changes over time.
The Map View utilizes scatter_geo to map each city’s temperature, while the Best Countries plot leverages a scatter plot to identify regions with favorable temperature trends.
