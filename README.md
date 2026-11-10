# Restaurant Data Analysis

## Project Overview
This project explores a restaurant dataset using Python and data analysis techniques. It focuses on understanding restaurant distribution, customer ratings, cuisine preferences, pricing, online delivery availability, and restaurant-chain performance.

The analysis is organized into separate Jupyter notebooks, with visualizations and a geographic map to make patterns easier to understand.

## Objectives
- Analyze restaurant distribution across cities.
- Identify popular cuisines and cuisine combinations.
- Study restaurant ratings and customer votes.
- Examine restaurant price-range distribution.
- Compare ratings for restaurants with and without online delivery.
- Evaluate the performance of restaurant chains.
- Visualize the geographic distribution of restaurants.

## Technologies Used
- **Python** – data analysis
- **Pandas** – data loading, cleaning, grouping, and analysis
- **Matplotlib** – charts and visualizations
- **Folium** – interactive geographic map
- **Jupyter Notebook / Google Colab** – development environment

## Project Structure

```text
Restaurant data Analysis/
│
├── Dataset .csv
├── City-wise Restaurant Analysis.ipynb
├── Cuisine Combination Analysis.ipynb
├── Geographic Distribution of Restaurants (Map Analysis).ipynb
├── Online Delivery Impact Analysis.ipynb
├── Price Range Distribution Analysis.ipynb
├── Restaurant Chain Performance Analysis.ipynb
├── Restaurant Ratings & Votes Analysis.ipynb
├── Top Cuisines Analysis.ipynb
└── Outputs/
    └── Visualization screenshots
```

## Analysis Modules

| Notebook | Description |
|---|---|
| City-wise Restaurant Analysis | Counts restaurants by city and compares average ratings across cities. |
| Top Cuisines Analysis | Identifies the most common individual cuisines by splitting cuisine entries into separate values. |
| Cuisine Combination Analysis | Examines frequently occurring cuisine combinations and their average ratings. |
| Restaurant Ratings & Votes Analysis | Studies the distribution of aggregate ratings, the most common rating, and average votes. |
| Price Range Distribution Analysis | Analyzes the number and percentage of restaurants in each price range. |
| Online Delivery Impact Analysis | Compares online-delivery availability and average ratings for delivery categories. |
| Restaurant Chain Performance Analysis | Identifies restaurant names appearing more than once and compares their average ratings and votes. |
| Geographic Distribution of Restaurants | Uses latitude and longitude data to display restaurant locations on an interactive Folium map. |

## Installation

Make sure Python is installed. Install the required libraries:

```bash
pip install pandas matplotlib folium jupyter
```

## How to Run

1. Download or clone this repository.
2. Keep `Dataset .csv` in the same folder as the notebooks.
3. Open a terminal in the project folder.
4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the notebook you want to explore.
6. Run the cells in order.

You can also upload the project files to **Google Colab** and open the notebooks there. If using Colab, make sure the dataset is uploaded or available at the file path used in the notebook.

## Dataset
The project uses `Dataset .csv`. The notebooks use fields such as city, restaurant name, cuisines, aggregate rating, votes, price range, online-delivery availability, latitude, and longitude.

Make sure the dataset is present at the path referenced by each notebook before running the analysis.

## Outputs
Charts are generated in the notebooks to show the results of the different analyses. The `Outputs/` folder contains screenshot files of selected results. The geographic analysis also creates an interactive map in the notebook.

## Key Skills Demonstrated
- Data cleaning and handling missing values
- Exploratory Data Analysis (EDA)
- Data grouping, aggregation, and percentage calculations
- Working with categorical and geographical data
- Data visualization
- Extracting insights from structured datasets

## Author
**[Your Name]**

---

*This project was created for learning and demonstrating practical data analysis skills using Python.*
