# Data Visualisation with R - Irish Covid Cases for each day per county.
 Visualisation using R of a data set of Irish covid case numbers per county.

To view the visuals, refer to the `22222806_Assignment 2.pdf` file. For code, refer `Assignment 2.Rmd` file.

# University of Galway
## CT5100 - Data Visualisation

## 1. Problem Statement

In this assignment you are required to visualise a data set of Irish covid case numbers per county. 

### Data 
The data is contained in the attached zip file. Unzip it and place all the files in your developement folder for assignment 2. 

The main file is the .shp file. This type of file is known as a shape file and contains data used to plot values on a map using colour to indicate the value assigned to a particular region on the map. You should consult the tutorial on choropleths in week 4's learning materials on how to read and use the shape files supplied for this assignment. Even though all the data for this assignment is contained in the .shp file, all files in the zip file are required by chloropleth visualisation packages (not just ggplot2). These files must be included, unaltered in the same folder as the .shp file if your choropleth visualisation is to work. 

The shape file contains the following data fields: 
* CountyName : the name of the Irish county. E.g. Galway, Cork, Carlow 
* Population: The population of the county according to the last census 
* TimeStamp: the date at which each data value is measured e.g. "2021-12-21" 
* DailyCCase: the number of new confirmed cases reported for the date in the timestamp 
* ConfirmedC: the cumulative (total) number of confirmed cases up to the date in the timestamp 
* geometry: the geographical shape coordinates of the county which allows it to be plotted in a choropleth

## 2. Visualisation Questions

In this assignment you are required to one visualisation for each question from this data (If you submit more than one, I will only mark the first). 
1. A visualisation that allows the reader to accurately compare the cumulative number of cases per 100,000** of population per county on the 21 December 2021. County Galway should be highlighted. 
2. A visualisation that allows the reader to read how each county diverges from from the mean cumulative number of cases (per 100,000) in the country as at the 21 December 2021. You may also use a daily figure in this section. County Galway should be highlighted.
3. A visualisation showing the daily number of confirmed covid cases in one county in Ireland for a 18-week period. This visualisation should help the reader to perceive the trend in the data. 
4. A visualisation that highlights the cumulative number of cases per 100,000 in Galway and two other counties representing counties that have had the lowest and highest number of cases per 100,000 over the full timeline of the dataset. The visualisaton must also show the cumulative case number for all other counties in Ireland in the same plot. However, the three selected counties (Galway and two other counties) must be highlighted).
5. A choropleth visualisation of the counties of Ireland showing total new confirmed cases (per 100,000) for a 4-week period (of your choice) for each county. The choropleth should show how each county diverges from the mean number of new confirmed cases (per 100,000) per county for that 4-week period.

