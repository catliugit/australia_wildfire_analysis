# Analyzing Wildfire Activities in Australia - Coursera Practice Assignment
Overview
This project analyzes wildfire activities in Australia using various data visualization techniques. It is part of the "Data Visualization with Python" course on Coursera.

# Course Information
Course Name: Data Visualization with Python on Coursera
Instructor: [Dr. Pooja]

# Objectives
- Use Matplotlib, Pandas, Seaborn, and Folium to create informative plots and charts
- Visualize geographical data using Folium
- Analyze trends and patterns in wildfire activities in Australia

# Dataset
- Time Frame: Data on fire activities in Australia starting from 2005.
- Regions: 7 distinct regions.
- Variables:
Date: UTC timestamp, with data for 24 hours ahead.
- Estimated Fire Area: Daily sum of estimated fire area (in km²) with > 75% confidence for each region.
- Mean Estimated Fire Brightness: Daily mean of fire brightness (in Kelvin) based on flagged fire pixels with > 75% confidence.
- Mean Estimated Fire Radiative Power: Daily mean radiative power (in megawatts) with > 75% confidence.
- Mean Confidence: Daily mean confidence level for fires with > 75% confidence.
- Std Confidence: Standard deviation of radiative power (in megawatts).
- Var Confidence: Variance of radiative power (in megawatts).
- Count: Daily number of pixels for fires with > 75% confidence.
- Replaced: Indicates if data has been replaced with higher-quality standard data (marked as 'Y' for replaced data, typically with a 2-3 month lag).

# Modifications and Enhancements
- Additional Data Visualizations: Added more comprehensive visualizations to provide deeper insights into the wildfire data.
- Enhanced Data Preprocessing: Improved data cleaning and preprocessing steps to ensure higher accuracy and reliability of the visualizations.
- Interactive Maps with Folium: Created interactive maps to visualize wildfire activities across different regions in Australia.
- Extended Analysis: Conducted further analysis to identify potential causes and patterns of wildfires.

# Steps
# Download Required Libraries:
In VSCode, install Seaborn and Folium using the instructions provided in this file.

# Open Jupyter Notebook:
- Go to File > New File and select "Jupyter Notebook" to create a new .ipynb file.

# To view and run the code, follow these steps:
- Install VS Code: Make sure you have Visual Studio Code installed.
- Install the Jupyter Extension: In VS Code, go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X on macOS) and install the "Jupyter" extension.
- Open the Source File: Download or clone the repository and open the [Source File](https://github.com/catliugit/australia_wildfire_analysis/commit/819c3ebf60c40fb9d9d3b67867e5a3f151f3f322) in VS Code.
- Run the Code: Use the Jupyter Notebook interface in VS Code to run the code cells. The code sections are annotated and organized as follows:
- PREVIEW: Jupyter Notebook cells with Python code.
- CODE: Sections in JSON format.
