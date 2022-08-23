# Ford GoBike Data Exploration and Visualization

## by Glory Temitayo Andrew


## Investigation

> This project has two parts that illustrates the importance and value of data visualization techniques in the data analysis process.

> In the first part, I used python visualization libraries to systematically wrangle and explore a dataset, 201902-fordgobike-tripdata.csv, starting from plots of single variables and building up to plots of multiple variables.

> In the second part of the project, I will produced a short presentation that illustrates interesting properties, trends and relationships that I discovered in the selected cleaned datasets from the first part.

## Dataset
>This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset was stored a pandas dataframe which has 183412 records and 16 features.

## Summary of Findings
Reading the csv file, I cleaned the dataset and make some neccessary ajustment.

#### Data wrangling to create clean dataset 
I did a little wrangling and cleaning of data which is stated as follows:<br><br>
1. Converted start_time and end_time into a datetime datatype<br>
2. Converted member_birth_year into an integer datatype<br>
3. Converted start_station_id, end_station_id, and bike_id into a string datatype<br>
4. Dropped all the records that have missing values in any of the features<br>
5. Created a new column named member_age gotten member_birth_year<br>
6. For a less complicated view, I added a column converting the duration from sec to min<br>

#### Summary of Findings of Data Exploration
After the exploration was complted, I submitted that:
1. There was an establishment of the fact that those who use bikes as a mode of transportation do so more on weekdays than on weekends, with peak hours being when they ride to and from work/school.

2. The duration of trips during the week is much less than on weekends for both user types

3. Younger people tends to travel shorter distance than older ones

## Key Insights for Presentation
1. I started this presentation showing the correlation between Age and Trip duration
2. Then, I tried to figure out the busiest day of the week. This was achieved by exploring trip duration and days of the week with the use of seaborn's catplot.
3. This section was concluded by showing the relationship between trip duration, user type and gender also presented by a catplot.