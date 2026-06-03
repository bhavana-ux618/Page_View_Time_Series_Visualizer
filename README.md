# Page View Time Series Visualizer

## Overview

This project is part of the freeCodeCamp Data Analysis with Python Certification. The objective is to analyze and visualize time-series data from the freeCodeCamp forum using Python data visualization libraries.

The dataset contains the daily number of page views on the freeCodeCamp forum from May 2016 to December 2019. Through various visualizations, the project highlights trends, seasonal patterns, and growth in forum activity over time.

## Features

* Imports and cleans time-series data using Pandas.
* Removes extreme outliers from the dataset.
* Creates a line chart to visualize daily page views over time.
* Generates a bar chart showing average monthly page views grouped by year.
* Produces box plots to analyze yearly trends and monthly seasonality.
* Saves all generated visualizations as image files.

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* NumPy

## Dataset

**File:** `fcc-forum-pageviews.csv`

The dataset contains:

* Date
* Daily Page Views

Data covers the period:

**May 2016 – December 2019**

## Visualizations

### 1. Line Plot

Displays daily page views over time to identify overall growth trends.

**Output:** `line_plot.png`

### 2. Bar Plot

Shows average monthly page views grouped by year.

**Output:** `bar_plot.png`

### 3. Box Plots

Two box plots are generated:

* **Year-wise Box Plot (Trend)** – shows the distribution of page views across different years.
* **Month-wise Box Plot (Seasonality)** – shows seasonal patterns and monthly variations.

**Output:** `box_plot.png`

## Project Structure

```text
page-view-time-series-visualizer/
│
├── fcc-forum-pageviews.csv
├── time_series_visualizer.py
├── main.py
├── test_module.py
├── requirements.txt
├── README.md
├── line_plot.png
├── bar_plot.png
└── box_plot.png
```

## Installation

Clone the repository:

```bash
git clone <your-repository-url>
```

Navigate to the project folder:

```bash
cd page-view-time-series-visualizer
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the project:

```bash
python main.py
```

Generated files:

* line_plot.png
* bar_plot.png
* box_plot.png

## Learning Outcomes

Through this project, I learned:

* Time-series data analysis
* Data cleaning and outlier removal
* Data aggregation using Pandas
* Building line charts, bar charts, and box plots
* Visualizing trends and seasonality in real-world datasets
* Creating professional data visualizations with Matplotlib and Seaborn

## Skills Demonstrated

* Data Analysis
* Data Visualization
* Pandas
* Matplotlib
* Seaborn
* Python Programming
* Statistical Data Exploration

## Acknowledgements

This project was completed as part of the freeCodeCamp Data Analysis with Python Certification.

## Author

Bhavana R
