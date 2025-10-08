# Pair-project
Sports Car Data Analysis
This repository contains a Jupyter Notebook that performs an exploratory data analysis on a dataset of sports cars. The analysis includes visualizations and summary statistics to understand various aspects of the data, such as price trends, engine characteristics, and manufacturer performance.

Notebook Contents
The analysis is structured into several sections within the notebook, each addressing a different area of the sports car dataset.

Setup and Imports
This initial section sets up the environment by importing necessary Python libraries for data manipulation and visualization, including pandas, numpy, matplotlib.pyplot, and seaborn. It also configures plotting styles and handles potential warnings.

Year Analysis
The year_analysis function explores the dataset based on the year of manufacture. It generates two plots:

Price Trend by Year: This plot (visible in the notebook output below the corresponding code cell) shows how the average price of sports cars has changed over the years, with error bars indicating the variability in prices for each year. This helps identify price trends and fluctuations.
Models by Year: This bar chart (also in the notebook output for the year_analysis cell) illustrates the number of new sports car models introduced each year, providing insights into the volume of production over time.
Engine Size Analysis
The engine_analysis function focuses on the characteristics of the cars' engines. It produces two visualizations:

Engine Size Distribution: A histogram (displayed in the notebook output for engine_analysis) showing the frequency of different engine sizes in the dataset. This helps understand the common engine sizes among sports cars.
Power Efficiency by Brand: A box plot (part of the engine_analysis output) that compares the horsepower generated per liter of engine displacement across different manufacturers. This highlights which brands are more efficient in terms of power output relative to engine size.
Price Analysis
The price_analysis function provides a detailed look at the distribution of sports car prices. It generates:

Price Distribution: A histogram (shown in the notebook output for price_analysis) illustrating the frequency of different price points. Lines on the histogram indicate the mean and median prices, helping to understand the typical price range and any skewness in the distribution.
Price Box Plot: A box plot (also in the price_analysis output) offering a visual summary of the price distribution, including quartiles and potential outliers. This provides a quick overview of the spread and central tendency of prices.
Manufacturer Analysis
The manufacturer_analysis function examines the dataset from the perspective of different manufacturers. It creates three plots:

Market Share: A pie chart (in the notebook output for manufacturer_analysis) showing the proportion of cars from the top manufacturers in the dataset, indicating their market presence.
Average Price by Make: A bar chart (part of the manufacturer_analysis output) displaying the average price of cars for the top manufacturers, allowing for easy comparison of pricing strategies between brands.
Price Range by Brand: A box plot (also in the manufacturer_analysis output) illustrating the distribution of prices for the top manufacturers, showing the variability in pricing within each brand and identifying potential outliers.
Summary Statistics
The format_summary_statistics function (code and output visible in the notebook) generates a detailed table of descriptive statistics for all numerical columns in the dataset. This table includes important measures such as count, mean, standard deviation, minimum, maximum, and quartiles, providing a comprehensive quantitative summary of the data.

How to View the Outputs
All the generated graphs and the summary statistics table are displayed directly within the output cells of the Jupyter Notebook. To view them, simply run the code cells in sequence.
