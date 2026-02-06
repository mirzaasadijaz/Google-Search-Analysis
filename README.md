# Google Searching Keywords Analysis project
This repository contains a specialized Google Search Analysis project that leverages the pytrends library to analyze real-time search engine data. The project focuses on visualizing search interest trends over time, specifically targeting the "Data Science" field and comparing it across different keywords.

# 🚀 Project Overview
The objective of this analysis is to harness Google Trends data to understand public interest and market demand. By using the Google API, the project retrieves live data to identify seasonal peaks, geographical interest, and the comparative popularity of specific tech-related search terms.

# 📊 Key Features & Analysis
Live Data Integration: Uses the pytrends API to connect directly to Google Trends, specifically configured for the Pakistan timezone (tz=-300).

Keyword Trend Analysis: - Analyzing the historical interest of the keyword "Data Science" over a specific time horizon.

Identifying "Interest Over Time" to see if the field is growing, stagnating, or declining.

Comparative Analysis: - Comparing multiple related keywords (e.g., "Data Science" vs. "Machine Learning") to see which topics dominate the search landscape.

Utilizing melted dataframes for compatibility with advanced Seaborn line plots.

Data Visualization: - Time-Series Plots: Clean, line-based visualizations using Seaborn and Matplotlib with a whitegrid style for high readability.

Interactive Charts: Using Plotly Express for dynamic exploration of search peaks.

# 🛠️ Tools & Libraries
Python 3

Pytrends: The pseudo-API for Google Trends.

Pandas: For data restructuring and time-series manipulation.

Matplotlib & Seaborn: For static, publication-quality trend graphs.

Plotly: For interactive web-ready visualizations.

# 📈 Insights Preview
The analysis identifies specific months where interest in "Data Science" spikes, potentially correlating with university admission cycles or major industry conferences.

Comparative plotting reveals how "Data Science" stacks up against other trending tech keywords in terms of total search volume.
