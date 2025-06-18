
# Zomato Exploratory Data Analysis (EDA)

This repository contains a Python-based exploratory data analysis (EDA) project using the Zomato dataset. The goal is to uncover insights about restaurants, cuisines, ratings, delivery services, and geographic distribution using Python data analysis libraries.

## Features

- **Data Cleaning and Preprocessing:** Handles missing values, renames columns, and merges datasets.
- **Country Mapping:** Uses an external Excel sheet to map country codes to country names.
- **Restaurant Analysis:** Identifies top cuisines, restaurant chains, and rating trends.
- **Online Delivery & Table Booking Insights:** Analyzes which countries and cities support these services.
- **Visualization:** Uses plots to display distributions, comparisons, and heatmaps for intuitive insights.

## Installation

To set up and run the notebook locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/zomato-eda.git
   cd zomato-eda
   ```

2. **Install the required packages:**
   ```bash
   pip install pandas
   pip install numpy
   pip install matplotlib
   pip install seaborn
   pip install openpyxl
   ```

3. **Open the Jupyter Notebook:**
   ```bash
   jupyter notebook zomato_EDA.ipynb
   ```

## Usage

1. **Start the notebook** and run the cells sequentially.
2. The dataset will be read from `zomato.csv` and merged with `Country-Code.xlsx`.
3. Multiple plots and insights will be generated throughout the notebook.
4. You can modify filters or grouping logic to explore additional insights (e.g., change rating thresholds or cuisine filters).

## Code Structure

The project includes the following key components:

- **`zomato_EDA.ipynb`** – Contains all data loading, cleaning, merging, analysis, and visualization steps.
- **`zomato.csv`** – Primary dataset containing restaurant information.
- **`Country-Code.xlsx`** – Excel sheet with country code mappings.

Key processes include:

- Loading datasets and merging them.
- Identifying country-wise and city-wise trends.
- Analyzing cuisines and restaurant ratings.
- Examining the availability of delivery and table booking options.

## Dependencies

The following Python libraries are required:

- `pandas`: For data manipulation and analysis
- `numpy`: For numerical operations
- `matplotlib`: For data visualization
- `seaborn`: For statistical visualizations
- `openpyxl`: For reading Excel files

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests to improve analysis, add visualizations, or extend the project.

## License

This project is licensed under the MIT License – see the LICENSE file for details.
