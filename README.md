# 911 Calls Analysis and Visualization in Montgomery County, PA
<p>This Python project focuses on the analysis and visualization of a dataset containing 911 emergency calls in Montgomery County, PA. The analysis utilizes popular data manipulation and visualization libraries such as Pandas, NumPy, Seaborn, and Matplotlib.</p>
Features
<ul>
  <li><strong>Data Import:</strong> The project begins by importing necessary libraries and loading the 911 call dataset into a Pandas DataFrame.</li>
  <li><strong>Data Exploration:</strong> Provides an overview of the dataset structure, including data types, non-null counts, and memory usage.</li>
  <li><strong>Top 5 Zipcodes and Townships:</strong> Identifies the top 5 zipcodes and townships with the highest number of 911 calls.</li>
  <li><strong>Reason Categorization:</strong> Introduces a new 'Reason' column derived from the 'title' column to categorize the type of emergency (EMS, Fire, Traffic).</li>
  <li><strong>Time Analysis:</strong> Extracts timestamp information and creates additional columns for hour, month, day of the week, and day.</li>
  <li><strong>Temporal Analysis:</strong> Utilizes countplots and line plots to analyze call trends over months, days of the week, and hours.</li>
  <li><strong>Heatmaps and Clustermaps:</strong> Generates visualizations using Seaborn to showcase patterns in 911 calls by day of the week and hour.</li>
</ul>
Requirements
<ul>
  <li>Python 3.x</li>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>Seaborn</li>
  <li>Matplotlib</li>
</ul>
Usage
<ol>
  <li>Install the required libraries using <code>pip install -r requirements.txt</code>.</li>
  <li>Run the provided Python script to execute the analysis.</li>
</ol>
<p>Feel free to explore the code, modify it, and adapt it to your specific needs. Happy coding!</p>
