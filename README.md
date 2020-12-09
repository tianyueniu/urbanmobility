# Urban Mobility Project


**About**:  
This projects uses the transportation network company (TNC) data released by the city of chicago to replicate a CMAP study on transportation in python (originally done in R). The project  provides an overview of the demand of Uber/Lyft in the different areas of Chicago. Large-scale computing techniques were applied to process 100+ million rows of data. It was found that economic status can significantly impact people's ride-hailing choices.

**Topics Explored**:  
Topic 1: General Demand for Ride-Hailing Services  
Topic 2: Geographic Distribution of Ride-Hailing Services  
Topic 3: Evaluation of Congestion  
Topic 4: Evaluation of Ride-Sharing   

**Packages Required**:   
dask, geopandas, pandas, shapeley, numpy, seaborn, matplotlib and urllib.   

**Files**:  
- census2010.zip: this includes Chicago census tracts shapefile that is readily available from https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Census-Tracts-2010/5jrd-6zik  
- tnc_data_report.ipynb: the codes that I've used to create all the visualizations
- data used in tnc_data_report.ipynb: the transportation network companies (TNC) data is readily availble from https://data.cityofchicago.org/Transportation/Transportation-Network-Providers-Trips/m6dm-c72p. The data I used was downloaded from the website on 2019 Oct 21st. The data is regularly updated on the Chicago Data Portal and can be downloaded easily.

**Acknowledgement**:  
For anyone who's interested in learning more about how to visualize geo-spatial data, I recommend a great course here: https://automating-gis-processes.github.io/site/. I learned everything from this course.
