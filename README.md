# Data Visualization & Python Libraries – Assignment 1

This repository contains solutions to **Assignment-1** based on Python libraries and data visualization using **NumPy**, **Pandas**, **Matplotlib**, **Seaborn**, and **Plotly**.

---

## Questions Overview

### Q1. Trigonometric Plot
- Generated 400 points from 0 to 4π using NumPy.
- Computed `y1 = sin(x)` and `y2 = cos(x/2)`.
- Plotted both on the same axes (sin: solid blue, cos/2: dashed red).
- Added title, labels, and legend. Saved the figure as PNG.

### Q2. Iris Dataset Analysis
- Loaded Iris dataset from seaborn GitHub.
- Computed mean sepal length per species.
- Plotted means as a vertical bar chart with annotated values.

### Q3. Spotify Top-50 Dataset
- Loaded dataset from GitHub using pandas.
- Used Seaborn to create a pairplot of numeric features:
  - `danceability`, `energy`, `valence`, `instrumentalness`.
- Colored points by genre, set style to `darkgrid`.

### Q4. Simulated Normal Distributions
- Simulated:
  - A ~ N(0, 1)
  - B ~ N(2, 1.5)
- Created a 2x1 subplot:
  - Top: overlapping histograms with transparency.
  - Bottom: side-by-side box plots.
- Added super-title and adjusted layout.

### Q5. Interactive Gapminder Plot
- Used built-in `gapminder` dataset from `plotly.express`.
- Filtered for year 2007, computed average life expectancy and GDP per capita.
- Created interactive bubble chart:
  - x-axis: GDP per capita
  - y-axis: life expectancy
  - bubble size: population
  - color: continent
  - hover: country name
- Added animation dropdown for years 1960–2007.

---

## Libraries Used
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `plotly.express`

---

## Visuals & Outputs
Plots and interactive charts are embedded and saved in the notebook.

---

## License
For educational use only. Attribution required if reused.

---

## Acknowledgements
- Seaborn and Spotify datasets from public GitHub repos.
- Gapminder via Plotly built-in samples.
