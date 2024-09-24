**Project Name:** Folklore

**Description:**

Folklore is a nutritional data visualization web application that allows users to explore various datasets related to food, health, and economics. Here are some of the functionalities offered by Folklore:

* **Recipe Search:** Users can search for recipes or regions using a provided search bar. The application retrieves recipe links and displays information about matching recipes and regions from the dataset. 
* **Obesity Data Exploration:** Folklore enables users to visualize global and regional obesity data through interactive charts. Users can explore data by country and see how obesity rates vary across different regions and age groups.
* **CO2 Emissions:** The application displays a map where users can see the CO2 emissions of different countries in 2020.
* **Nutritional Data Comparison:** Users can compare the average consumption of various nutrients (protein, carbohydrates, fiber, etc.) across a maximum of six countries. Both pie and radar charts are provided to visualize these comparisons.

**Data Sources:**

The application utilizes various datasets to provide the functionalities mentioned above. Here's a list of the datasets used:

* Finalized_KamerHoca_dataset.csv (Recipe data)
* [https://raw.githubusercontent.com/EnesAkkusci/Proj201-Datasets/main/Datasets/Obese%20Data.csv](https://raw.githubusercontent.com/EnesAkkusci/Proj201-Datasets/main/Datasets/Obese%20Data.csv) (Obesity data)
* [https://raw.githubusercontent.com/EnesAkkusci/Proj201-Datasets/main/Datasets/obsdfinal.csv](https://raw.githubusercontent.com/EnesAkkusci/Proj201-Datasets/main/Datasets/obsdfinal.csv) (Obesity data)
* [https://raw.githubusercontent.com/EnesAkkusci/Proj201-Datasets/main/Datasets/historical_emissions2.csv](https://raw.githubusercontent.com/EnesAkkusci/Proj201-Datasets/main/Datasets/historical_emissions2.csv) (CO2 emission data)
* [https://raw.githubusercontent.com/EnesAkkusci/Proj201-Datasets/main/Datasets/final.csv](https://raw.githubusercontent.com/EnesAkkusci/Proj201-Datasets/main/Datasets/final.csv) (Country-to-region mapping)
* Multiple CSVs containing nutritional data for various nutrients (protein, carbohydrates, etc.) (Source links are provided in the code)
* [https://raw.githubusercontent.com/EnesAkkusci/Proj201-Datasets/main/Datasets/faostatnewv.csv](https://raw.githubusercontent.com/EnesAkkusci/Proj201-Datasets/main/Datasets/faostatnewv.csv) (Economic data)

**Code Structure:**

The code is primarily written in Python and utilizes the following libraries:

* Dash: web framework for building analytical web apps
* Dash Bootstrap Components: components for styling Dash apps
* Plotly.express: for creating basic charts
* Pandas: data manipulation library
* Requests: for making API calls

The code is well-structured and organized. It consists of several components:

* Layout: Defines the overall structure of the web application using Dash components.
* Callbacks: Define how the application should update based on user interactions (e.g., selecting a country, clicking on a chart).
* Helper functions: Reusable functions that perform specific tasks (e.g., loading data, creating charts).

**Running the Application:**

1. Ensure you have Python and the required libraries installed (`pip install dash dash-bootstrap-components plotly pandas requests`).
2. Save the code in a Python file (e.g., `folklore.py`).
3. Run the application using the following command: `python folklore.py`
4. Open http://127.0.0.1:8050/ in your web browser to access the Folklore application.

**Additional Notes:**

* The code retrieves recipe links using the Google Custom Search API. A valid API key is required for this functionality to work. You can obtain a free API key from Google Cloud Platform.
* The readme.md file provides a comprehensive overview of the application's functionalities, data sources, code structure, and instructions for running it. 