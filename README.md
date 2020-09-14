# Coursera-Capstone-Project
A capstone project created for the completion the IBM Professional Data Science Certification


## Overview
The highest level description of this project is: _using K-means to automatically cluster areas of a city based on the distributions of venues within that cluster as a tool for planning a trip_

Clusters are generated dividing up a approximately 10 mile area into 0.5 mile clusters
![All clusters](https://github.com/dalcantara7/Coursera-Capstone-Project/blob/master/images/high%20level.png)

Clusters are color coded based on their distribution of venues so similarly colored clusters will have the similar types of venues 
![Cluster color coordination](https://github.com/dalcantara7/Coursera-Capstone-Project/blob/master/images/multiple%20clusters.png)

The details for every venue within cluster can be accessed by tapping the dot associated with that venue
![individual venue](https://github.com/dalcantara7/Coursera-Capstone-Project/blob/master/images/details.png)


### Limitations
Because of the unsupervised nature of K-means, sometimes not all venues are captured within a 0.5 mile cluster. The below image shows how widely the amount of excluded venues can vary

![graph of excluded](https://github.com/dalcantara7/Coursera-Capstone-Project/blob/master/images/exluded%20graph.png)

### Write Up
The best way to view this tool is to download the capston notebook and place the coordinates of the center of the your city of interest. You will also need a Foursqaure API key. However, there is a write up and presentation of the tool available for a quick glance to avoid the hassle.

The full write up for this project can be viewed [here](https://github.com/dalcantara7/Coursera-Capstone-Project/blob/master/Coursera%20Final%20Project%20Write%20Up.pdf)
The presentation can be viewed [here](https://github.com/dalcantara7/Coursera-Capstone-Project/blob/master/Coursera%20Capstone%20Presentation.pptx)


