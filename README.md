# CPSC 4530 – Data Visualization and Exploration (Spring 2025)

## Assignment 1: Visualizing Time-Oriented Data

**Due Date:** Monday, February 10, 2025, by 11:59 PM (Online Submission via UTC Canvas)

## Overview
Time is a fundamental dimension in many domains such as medicine, engineering, business, science, biography, history, planning, and project management. Understanding time-oriented data helps in learning from the past to predict, plan, and build the future. Due to the distinct characteristics of time, specific visualization and analytical methods are required.

A time-oriented dataset is characterized by time-varying semantics, where time is a key attribute. A common form of time-oriented data is a time-series dataset, which consists of an ordered sequence of time-value pairs. These pairs are often but not always spaced at uniform intervals. Typical analysis tasks include identifying trends, correlations, and variations across different time scales (hourly, daily, weekly, seasonal, etc.).

## Key Concepts
### Mapping of Time
There are two ways to represent time in visualization:
1. **Mapping Time to Space**: Data and time are displayed in a static, single coherent representation that does not change over time.
2. **Mapping Time to Time**: Time is used as a dynamic element in the visualization, such as animations or slide shows that change automatically over time.

### Dimensionality of the Presentation Space
- **2D Representations**: The time axis is emphasized within the two available display dimensions.
- **3D Representations**: A third dimension can be dedicated to time, separating it from other data dimensions.

## Examples & Resources
To familiarize yourself with time-series data visualization in Python, consider:

1. Using AI tools like ChatGPT/Gemini to generate example Python code for time-series visualization.
2. Reviewing online resources:
   - [Time-Series Data Visualization with Python](https://machinelearningmastery.com/time-series-data-visualization-with-python/)
   - [Time-Series Data Visualization in Python](https://www.vshsolutions.com/blogs/time-series-data-visualization-in-python/)
   - [Time-Series Analysis with Python](https://www.machinelearningplus.com/time-series/time-series-analysis-python/)
   - [Formatting and Visualizing Time-Series Data](https://towardsdatascience.com/formating-and-visualizing-time-series-data-ba0b2548f27b)
   - [Handling Multiple Time-Series Data](https://towardsdatascience.com/8-visualizations-with-python-to-handle-multiple-time-series-data-19b5b2e66dd0)
   - [Time-Series Analysis & Visualization](https://kanoki.org/2020/04/27/time-series-analysis-data-visualization/)
   - [Introduction to Time-Series Forecasting](https://www.kaggle.com/iamleonie/intro-to-time-series-forecasting)
   - [YouTube Tutorials](https://www.youtube.com/watch?v=a9UrKTVEeZA) | [Alternative Video](https://www.youtube.com/watch?v=e8Yw4alG16Q)

## Assignment Requirements

### Task 1: Identify Time-Oriented Datasets
- Select **three** different time-series datasets.
- Possible sources include:
  - Websites listed in the course syllabus.
  - Datasets from previous projects or ongoing work.

### Task 2: Data Visualization & Analysis
- Use Python to visualize and explore trends/patterns in each dataset.
- Apply the two criteria:
  1. **Mapping of Time**
  2. **Dimensionality of Presentation Space**
- Refer to resources such as [TimeViz](http://www.timeviz.net/) and Chapter 7 of *Interactive Data Visualization: Foundations, Techniques, and Applications (Second Edition)* by Matthew O. Ward.

### Task 3: Report Preparation
Prepare a **Word/PDF report** describing your analysis, including:
1. **Dataset Overview**: 
   - Data source (with hyperlink if available)
   - Dataset type (table, network, tree, field, geometry, cluster, set, or list)
   - Data types (items, attributes, links, positions, or grids)
   - Attribute types and data semantics (real-world meaning of data)
2. **Preprocessing Steps**:
   - Data cleaning (e.g., handling missing values, subsetting, filtering, averaging)
3. **Visualization & Insights**:
   - Include figures of visualizations.
   - Explain trends, patterns, and outliers discovered.

## Submission Guidelines
Submit a **folder** (zipped or unzipped) via UTC Canvas containing:
- Your **report** (Word or PDF format)
- Your **Python code** (well-commented and complete)
- Dataset **webpage links** (no need to upload datasets)

---
*For additional guidance, refer to the example report provided in the Assignments folder on Canvas.*
