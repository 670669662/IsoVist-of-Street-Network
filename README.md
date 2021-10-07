
# IsoView of Street Network Comparison

## Introduction
The purpose of this grasshopper plug-in development is to facilitate urban designers and landscape designers to compare the value of isoview on the way when the road traffic reaches the green space. The plug-in is different from other isoview plug-ins in that it introduced the comparison between the most calculated distance and the specific IsoView value (Area, degree of closure, elongation, etc.), so as to facilitate the designer to compare the difference between the past and the current planning or the difference between different parts of the city.

Before You Start：

- Grasshopper in rhino 6/7
- Install “caribou”plugin（You can download it through rhino's package manager or food 4rhino）＆ “Decoding scape"(https://toolbox.decodingspaces.net/download-decodingspaces-toolbox/)
- Use open streetmap download data （You can download data from this website “openstreetmap.org/#map=5/38.007/-95.844”

Color and Graphic Display：
- orange：isoview bases on human position
- Black：Berlin Wall (or other city barrier)
- Green: Park area
- Pink: Start point
- Blue: End point

Note：
1. Please try to keep the OSM file size within 100mb, too large files will cause the plug-in to crash or the computer crashes
2. After loading the file, please give the computer a few minutes to extract the OSM data
3. Users can selectively turn on the isoview GPU acceleration module according to their computer configuration to increase the calculation speed

## Operating Procedures


https://user-images.githubusercontent.com/70087271/136328529-a438f5eb-c0fb-44ef-bd24-a2eee596ba21.mp4



Plugin Frame Work

![1633579496-01](https://user-images.githubusercontent.com/70087271/136319216-13f842a6-f79c-454e-b40d-489f7be45078.jpg)


Step 01-Data Collection

- _Use Caribou to select the main and secondary roads and sidewalks in urban traffic for analysis, and then select the park in leisure as the green space to be analyzed_
![s1_画板 1](https://user-images.githubusercontent.com/70087271/136331212-e235b778-6922-45d0-92e7-2c8579e55f83.jpg)


Step 02-Comparison Range Selection

https://user-images.githubusercontent.com/70087271/136333242-d59c8702-f408-4d67-847d-b26b575a50d5.mp4



- _The points to be analyzed are selected by splitting the Berlin Wall and the analysis range is generated, and then classified according to the east and west sides_

Step 03-Shortest Distance Calculation

- _Project the points generated by the park and the Berlin Wall to the street network to find the nearest point, and then import these data and the optimized street data into the shortest distance component to get the shortest distance to the east and west sides_

Step 04-IsoView Calculation

- _Use IsoView in decoding space for analysis, and finally get 17 IsoView-related values of specific points on each road_

Ste p05-IsoView Visulization

- _Use remap and gradient and loft to visualize the process of IsoView generation_


Step 06-HUman UI Data Visualization Production Charts

- _Use Human UI to compare the data horizontally and vertically. Including single data comparison; overall data comparison; data average comparison_

## Operating Reults

01.Static spatial Distance Comparison

![1633578597(1)](https://user-images.githubusercontent.com/70087271/136317653-188eb4e0-609a-4659-ac7b-57117a2e7682.png)

02.Comprehensive IsoView Data Comparison



![1633578957(1)](https://user-images.githubusercontent.com/70087271/136317831-e74c7f1e-27e8-48fe-b8e2-6f03004c948d.png)


03.Individual IsoView Data Comparison

![1633578508(1)](https://user-images.githubusercontent.com/70087271/136317841-f5473a63-8d88-4588-a283-39b9f325a5f1.png)














## Reference
https://toolbox.decodingspaces.net/tutorial-2d-and-3d-isovists-for-visibility-analysis/

https://caribou.philipbelesky.com/



