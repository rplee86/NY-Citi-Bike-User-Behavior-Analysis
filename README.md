# Python: User Behavior Analysis
Utilizing Python and Tableau for an in-depth exploratory analysis of business data.

[Link to the Tableau Storyboard](https://public.tableau.com/app/profile/ryan.lee1243/viz/NYCitiBikeUserBehaviorAnalysis/NYCitiBikeStory)

## Objective
The project aims to uncover information about the customer base of [NY Citi Bike](https://citibikenyc.com/) and how they use NY Citi Bikes during March 2019. The relevant insights uncovered are then used to build a storyboard via [Tableau](https://public.tableau.com/).

### Key Questions:
- What day and time do NY Citi Bike users rent the least/most frequently? How does this vary across age group? User type? Gender?
- What are the most popular pick-up and drop-off locations across the city?
- How does trip duration vary across age group? User Type? Days of the week? Gender?
- Which age group rents bikes least/most frequently?
- How does bike rental vary across user type/age group/gender on different days of the week?
- Do users' age impact the bike trip duration?

## Content
**1 Project Information**
- [Project Information](https://github.com/ryanpatricklee/User-Behavior-Analysis/blob/main/01%20Project%20Information/NY%20Citi%20Bike%20Analysis.pdf)

**2 Prepared Data**
- [nyc-zip-code-tabulation-areas-polygons.geojson](https://github.com/ryanpatricklee/User-Behavior-Analysis/blob/main/02%20Prepared%20Data/%20nyc-zip-code-tabulation-areas-polygons.geojson)

**3 Scripts**
- [Data Preparation](https://github.com/ryanpatricklee/User-Behavior-Analysis/blob/main/03%20Scripts/1.%20Data%20Preparation.ipynb)
- [Exploring Relationships](https://github.com/ryanpatricklee/User-Behavior-Analysis/blob/main/03%20Scripts/2.%20Exploring%20Relationships.ipynb)
- [Geospatial Analysis](https://github.com/ryanpatricklee/User-Behavior-Analysis/blob/main/03%20Scripts/3.%20Geospatial%20Analysis.ipynb)
- [Regression Analysis](https://github.com/ryanpatricklee/User-Behavior-Analysis/blob/main/03%20Scripts/4.%20Regression%20Analysis.ipynb)
- [Cluster Analysis](https://github.com/ryanpatricklee/User-Behavior-Analysis/blob/main/03%20Scripts/5.%20Cluster%20Analysis.ipynb)
- [Time Series Analysis and Forecasting](https://github.com/ryanpatricklee/User-Behavior-Analysis/blob/main/03%20Scripts/6.%20Time%20Series%20Analysis%20and%20Forecasting.ipynb)

**4 Visualizations**

Data [visualizations](https://github.com/ryanpatricklee/User-Behavior-Analysis/tree/main/04%20Visualizations) created using
- matplotlib
- seaborn
- scikit-learn

Visualizations were then recreated in Tableau to create a storyboard. The storyboard doesn’t contain every insight uncovered in the python analysis; it contains only those that were relevant to the storyboard.

## Data
[March 2019 NY Citi Bike trip data](https://s3.amazonaws.com/tripdata/201903-citibike-tripdata.csv.zip)
