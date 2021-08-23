# SIADS697-JNH
This is the github repository for Julia Wu, Nicholas Martin, and Hyungmook Oh for their SIADS Capstone Project

The notebooks created within this project illustrates the process that lead to our Airbnb results. Two major areas, Hawaii and San Diego, are chosen due to their tourist heavy locations. There are two folders that have mirroring code to represent huge similarity in the results that lead to our definition of "success." This readme is to guide the reader through our notebooks, and navigate to files that are most significant to our analysis.

# Before Running Notebooks!
Please make sure everything from requirements.txt is installed. In order for Models.ipynb to run, you must first run the HI_dataset.ipynb and SD_dataset.ipynb. This will create the zipped datasets that the models notebook will read in.

## Main Folder

### SD-DataExploration.ipynb
Initial data exploration with San Diego listings data. Creates visuals to help us better understand the layout of San Diego in relation to POI, prices, and room types.

### Models.ipynb
Model exploration of the aggregated Hawaii and San Diego Datasets. Please refer to instructions under "Before Running Notesbooks" in order to successfuly run this notebook.

### Hawaii_Dashboard.pbix & San_Diego_Dashboard.pbix
These are the PowerBI Dashboards used to analyze and visualize the datasets.

## Hawaii
Contains datasets from both airbnb and poi factory for Hawaii. The csv files are in their respective folders for ease of access. The csv files outside of these folders are utilized specifically for the notebook code, as some are used specifically for certain scenarios.

### poi_factory
Csv datasets from poi-factory. Represents local attractions based on point of interest.

### HI_dataset.ipynb
Synthesizes listings, neighborhood, and calendar CSVs and joins these datapoints with the POI factory folder datasets.

### Folium with Hawaii.ipynb
Displays interactive heatmap of Hawaii that includes clusters of close attractions. Defines what was done to manipulate the dataset and create the visuals.

### kepler_heatmap.gl
Illustrates the interactive heatmap in a more dynamic 3D map. 


## San_Diego
Contains datasets from both airbnb and poi factory for San Diego. The csv files are in their respective folders for ease of access. The csv files outside of these folders are utilized specifically for the notebook code, as some are used specifically for certain scenarios.

### poi_factory
Csv datasets from poi-factory. Represents local attractions based on point of interest.

### SD_dataset.ipynb
Synthesizes listings, neighborhood, and calendar CSVs and joins these datapoints with the POI factory folder datasets.


### Folium_with_San_Diego.ipynb
Displays interactive heatmap of San Diego that includes clusters of close attractions. Defines what was done to manipulate the dataset and create the visuals.

### kepler_heatmap.gl
Illustrates the interactive heatmap in a more dynamic 3D map. 
