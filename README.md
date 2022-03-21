# covid-19-impact-project-spauster

The file Map.Rmd creates an R shiny app displaying COVID case data by day for every US county.

1. I read in the shapefiles for US counties and find the centroid
2. I read in data from teh NYT github with daily case and death counts by county
3. I merge the Case data with the shapefiles for each county
4. I create a test leaflet map with the most recent day of data
5. I create an R shiny app to plot the data with a slider to pick the day
