# Airline-Data-Analysis
## 1. Project Overview 
This project performs an end-to-end analysis of airline flight data using Python and industry-standard data analytics libraries. Through data cleaning, exploratory analysis, and visualization, it uncovers insights into airline operations, route networks, flight durations, and ticket pricing patterns.
## 2. Project Objective
This project aims to convert raw airline data into meaningful insights through data preprocessing, exploratory data analysis, and visualization. By examining factors such as airlines, routes, stops, flight duration, and ticket prices, the project seeks to identify patterns and trends within the dataset.
## 3. Tools Used 
The following tools and technologies were used in this project:

* Python – Core programming language used for data analysis.

* Pandas – Used for data cleaning, transformation, and analysis.

* NumPy – Used for numerical computations and data manipulation.

* Matplotlib – Used for creating static data visualizations.

* Seaborn – Used for statistical data visualization and enhanced plotting.

* Plotly – Used for interactive and dynamic visualizations.

* Jupyter Notebook – Used as the development environment for analysis and visualization.

## 4. Dataset 
Source : 
The raw dataset conatined the following fields:
* Airline
* Date_of_Journey
* Source
* Destination
* Route
* Dep_Time
* Arrival_Time
* Duration
* Total_Stops
* Additional_Info
* Price
* Duration in min
* No of Stops
* Days
* Payment for extra baggage

## 5. Steps Followed 

5.1. Data Preprocessing

  * Loaded and inspected the dataset.
  
  * Checked dataset shape, column names, data types, and missing values.
  
  * Replaced invalid values (?) with appropriate values.
  
  * Corrected and standardized column names for better readability.
  
  * Converted date and time columns to appropriate datetime formats.
  
  * Renamed Date_of_Journey to Dep_Date.
  
  * Extracted Arrival_Date and Arrival_Time_Only from the Arrival_Time column.
  
  * Standardized categorical values to ensure consistency.
  
  * Verified and corrected data types of columns.
  
5.2. Exploratory Data Analysis (EDA)

  * Generated descriptive statistics for numerical and categorical features.
  
  * Analyzed airline-wise flight distribution.
  
  * Examined source-wise and destination-wise flight frequencies.
  
  * Investigated route-wise flight distribution and route diversity.
  
  * Analyzed stop categories and stop-wise flight distribution.
  
  * Explored day-wise flight distribution.
  
  * Studied ticket price statistics and distribution.
  
  * Examined flight duration statistics and patterns.
  
  * Analyzed additional flight information categories.
  
  * Investigated passenger preferences for extra baggage payments.
  
  * Used NumPy and Pandas functions for statistical analysis and data exploration.
  
5.3. Data Visualization

  * Created airline-wise flight distribution charts.
  
  * Visualized source-wise and destination-wise flight traffic.
  
  * Generated stop-wise flight distribution visualizations.
  
  * Created day-wise flight distribution charts.
  
  * Visualized ticket price distribution using histograms.
  
  * Highlighted mean and median values in price distribution plots.
  
  * Generated route-based and category-based visualizations.
  
  * Used Matplotlib for foundational plotting.
  
  * Used Seaborn for statistical and enhanced visualizations.

  * Used Plotly for interactive and dynamic visualizations.
  
## 6. Key Insights

* Jet Airways operated the highest number of flights in the dataset, followed by IndiGo and Air India.

* Delhi was the busiest departure location, accounting for the largest share of flights.

* Cochin emerged as the most common destination, receiving the highest number of flights.

* The dataset contained 128 unique flight routes, indicating a diverse route network.

* The route DEL → BOM → COK was the most frequently used route.

* Flights with 1 stop were the most common, while flights with 3 or more stops were rare.

* Flight operations were distributed almost equally across all days of the week, showing no significant day-wise variation.

* The majority of flights had no additional information associated with them, while "In-flight meal not included" was the most common additional service category.

* More passengers opted to pay for extra baggage than those who did not.

* The average ticket price was approximately ₹9,087, while the median price was ₹8,372.

* Ticket prices showed a positively skewed distribution, with a small number of high-priced flights increasing the overall average.

* Most flight durations were concentrated in the lower and medium duration ranges, while very long-duration flights were relatively uncommon.

## 7. Screenshot

<img width="847" height="584" alt="image" src="https://github.com/user-attachments/assets/8a6c3ce4-65df-461e-a5e7-09dddc56e938" />

<img width="849" height="413" alt="image" src="https://github.com/user-attachments/assets/fb5de322-51fa-4f1c-90e7-294efb674224" />

<img width="850" height="453" alt="image" src="https://github.com/user-attachments/assets/68c90293-b5bb-4d4b-aa9d-01b5062c8222" />

<img width="840" height="548" alt="image" src="https://github.com/user-attachments/assets/fe4a8ad1-93d7-4675-bb6f-0789e60d671e" />

## 8. Files Included

* Airline_Data.csv – Raw airline dataset used for analysis.
  
* Airline_Main_Project.ipynb – Jupyter Notebook containing data preprocessing, exploratory data analysis (EDA), and visualizations.

