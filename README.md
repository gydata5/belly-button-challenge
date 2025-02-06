# Belly Button Challenge
The Belly Button Challenge is an interactive web dashboard built to visualize demographic and bacterial data samples. This project allows users to select a sample from a dropdown list and displays both a metadata panel and two types of charts (Bubble Chart and Bar Chart) to help understand the bacterial cultures found in different samples.

# Project Overview
The dashboard provides the following functionality:

1. Metadata Panel: Displays key demographic data associated with the selected sample.
2. Bubble Chart: Visualizes bacterial culture data by displaying the relationship between OTU IDs and sample values using a bubble chart.
3. Bar Chart: Shows the top 10 bacterial cultures found in the selected sample.

# Files in the Repository
* index.html: The main HTML file where the dashboard is built and displayed.
* app.js: Contains JavaScript code that fetches the data and builds the dashboard dynamically.
* samples.json: A sample data file containing bacterial culture data and metadata.
# Technologies Used
* HTML: For the webpage structure.
* JavaScript: To dynamically fetch data, build the metadata panel, and create visualizations using D3.js and Plotly.
* D3.js: A JavaScript library to manipulate documents based on data (used to build interactive visualizations).
* Plotly.js: A graphing library used to create the bubble and bar charts.

# How to Use
1. Clone or download this repository to your local machine.
2. Open index.html in a web browser to view the dashboard.

3. The dashboard will display:

* A dropdown list of sample names (IDs).
4. Once you select a sample, the metadata and charts (Bubble and Bar) will update accordingly.
5. You can interact with the dashboard by selecting different sample IDs from the dropdown. The charts and metadata will update dynamically based on the selected sample.

# How It Works
1. The page fetches data from the samples.json file.
2. The init() function populates the dropdown menu with sample IDs from the names field in the data.
3. When a sample is selected from the dropdown:
* buildMetadata() is called to display the demographic metadata associated with the sample.
* buildCharts() is called to generate a bubble chart and a bar chart to visualize bacterial culture data.
* 
# Contributing
* Fork the repository.
* Create a new branch.
* Make changes to the code.
* Submit a pull request with a description of your changes.
