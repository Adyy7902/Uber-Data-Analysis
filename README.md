# 👥🚖Uber-Data-Analysis
This document provides an overview of the conducted data analysis on Uber rides in USA from 2014 to 2015. The analysis utilizes various Python libraries for data manipulation, visualization, and exploration.

**Dataset:**

https://drive.google.com/drive/folders/1ZLUb8XDqKSC2IDN7hH9ljV_a8PMuX0z1?usp=sharing

**Analysis Highlights:**

* **Exploratory Data Analysis (EDA):**
    * Examined data distribution and identified potential patterns.
    * Cleaned and preprocessed the data for further analysis.
* **Rush Hour Detection:**
    * Analyzed ride frequency across different days, hours, and weeks.
    * Employed crosstab function to identify peak periods. 
    * Created point plots to visualize trends in rush hours.
* **Interactive Visualizations:**
    * Generated various plots using libraries like plotly to create interactive  visualizations for:
        * Bar plots
     
          ![Barplot](https://github.com/user-attachments/assets/0b84bc55-6674-4a96-80a3-e6527d53c983)

        * Box plots

          ![BoxPlot](https://github.com/user-attachments/assets/97127569-de66-4033-9765-c486f37fa23b)

        * Point plots
     
          ![PointPlot](https://github.com/user-attachments/assets/d1355978-0d53-4fdc-88ad-81e66b5776f3)


* **Spatial Analysis with Heatmap:**
    * Leveraged the folium library to create a heatmap on a world map, potentially visualizing ride density based on latitude and longitude values (assuming location data was available).
 
      ![Heatmap](https://github.com/user-attachments/assets/b1e7527d-2cf0-4a7e-96d2-4dbe85a61472)

**Packages Used:**

* pandas
* numpy
* matplotlib.pyplot
* plotly
* folium (for heatmaps)

